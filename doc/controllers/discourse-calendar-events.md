# Discourse Calendar-Events

```java
DiscourseCalendarEventsApi discourseCalendarEventsApi = client.getDiscourseCalendarEventsApi();
```

## Class Name

`DiscourseCalendarEventsApi`

## Methods

* [List Events](../../doc/controllers/discourse-calendar-events.md#list-events)
* [Export Events ICS](../../doc/controllers/discourse-calendar-events.md#export-events-ics)


# List Events

```java
CompletableFuture<ApiResponse<DiscoursePostEventEventsJsonResponse>> listEventsAsync(
    final IncludeDetails includeDetails,
    final Integer categoryId,
    final IncludeSubcategories includeSubcategories,
    final Integer postId,
    final String attendingUser,
    final LocalDateTime before,
    final LocalDateTime after,
    final Order order,
    final Integer limit)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `includeDetails` | [`IncludeDetails`](../../doc/models/include-details.md) | Query, Optional | Include detailed event information (creator, invitees, stats,<br>etc.) |
| `categoryId` | `Integer` | Query, Optional | Filter events by category ID |
| `includeSubcategories` | [`IncludeSubcategories`](../../doc/models/include-subcategories.md) | Query, Optional | Include events from subcategories when filtering by category |
| `postId` | `Integer` | Query, Optional | Filter to events associated with a specific post ID |
| `attendingUser` | `String` | Query, Optional | Filter to events where the specified user (username) has RSVP'd<br>as going |
| `before` | `LocalDateTime` | Query, Optional | Return events starting before this date/time (ISO 8601 format) |
| `after` | `LocalDateTime` | Query, Optional | Return events starting after this date/time (ISO 8601 format) |
| `order` | [`Order`](../../doc/models/order.md) | Query, Optional | Sort order for events by start date (default: asc) |
| `limit` | `Integer` | Query, Optional | Maximum number of events to return (default: 200)<br><br>**Constraints**: `>= 1`, `<= 200` |

## Response Type

**200**: success response (detailed)

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`DiscoursePostEventEventsJsonResponse`](../../doc/models/discourse-post-event-events-json-response.md).

## Example Usage

```java
discourseCalendarEventsApi.listEventsAsync(null, null, null, null, null, null, null, null, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Export Events ICS

```java
CompletableFuture<ApiResponse<InputStream>> exportEventsIcsAsync(
    final Integer categoryId,
    final IncludeSubcategories includeSubcategories,
    final String attendingUser,
    final LocalDateTime before,
    final LocalDateTime after,
    final Order order,
    final Integer limit)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `categoryId` | `Integer` | Query, Optional | Filter events by category ID |
| `includeSubcategories` | [`IncludeSubcategories`](../../doc/models/include-subcategories.md) | Query, Optional | Include events from subcategories when filtering by category |
| `attendingUser` | `String` | Query, Optional | Filter to events where the specified user (username) has RSVP'd<br>as going |
| `before` | `LocalDateTime` | Query, Optional | Return events starting before this date/time (ISO 8601 format) |
| `after` | `LocalDateTime` | Query, Optional | Return events starting after this date/time (ISO 8601 format) |
| `order` | [`Order`](../../doc/models/order.md) | Query, Optional | Sort order for events by start date (default: asc) |
| `limit` | `Integer` | Query, Optional | Maximum number of events to return (default: 200)<br><br>**Constraints**: `>= 1`, `<= 200` |

## Response Type

**200**: iCalendar file

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type `InputStream`.

## Example Usage

```java
discourseCalendarEventsApi.exportEventsIcsAsync(null, null, null, null, null, null, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

