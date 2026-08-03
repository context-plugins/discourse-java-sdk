# Badges

```java
BadgesApi badgesApi = client.getBadgesApi();
```

## Class Name

`BadgesApi`

## Methods

* [Admin List Badges](../../doc/controllers/badges.md#admin-list-badges)
* [Create Badge](../../doc/controllers/badges.md#create-badge)
* [Update Badge](../../doc/controllers/badges.md#update-badge)
* [Delete Badge](../../doc/controllers/badges.md#delete-badge)
* [List User Badges](../../doc/controllers/badges.md#list-user-badges)


# Admin List Badges

```java
CompletableFuture<ApiResponse<AdminBadgesJsonResponse>> adminListBadgesAsync()
```

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminBadgesJsonResponse`](../../doc/models/admin-badges-json-response.md).

## Example Usage

```java
badgesApi.adminListBadgesAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Create Badge

```java
CompletableFuture<ApiResponse<AdminBadgesJsonResponse1>> createBadgeAsync(
    final AdminBadgesJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`AdminBadgesJsonRequest`](../../doc/models/admin-badges-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminBadgesJsonResponse1`](../../doc/models/admin-badges-json-response-1.md).

## Example Usage

```java
badgesApi.createBadgeAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Badge

```java
CompletableFuture<ApiResponse<AdminBadgesJsonResponse2>> updateBadgeAsync(
    final int id,
    final AdminBadgesJsonRequest1 body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`AdminBadgesJsonRequest1`](../../doc/models/admin-badges-json-request-1.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminBadgesJsonResponse2`](../../doc/models/admin-badges-json-response-2.md).

## Example Usage

```java
int id = 112;
badgesApi.updateBadgeAsync(id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Delete Badge

```java
CompletableFuture<ApiResponse<Void>> deleteBadgeAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: success response

`void`

## Example Usage

```java
int id = 112;

badgesApi.deleteBadgeAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List User Badges

```java
CompletableFuture<ApiResponse<UserBadgesJsonResponse>> listUserBadgesAsync(
    final String username)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UserBadgesJsonResponse`](../../doc/models/user-badges-json-response.md).

## Example Usage

```java
String username = "username0";

badgesApi.listUserBadgesAsync(username).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

