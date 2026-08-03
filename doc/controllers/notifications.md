# Notifications

```java
NotificationsApi notificationsApi = client.getNotificationsApi();
```

## Class Name

`NotificationsApi`

## Methods

* [Get Notifications](../../doc/controllers/notifications.md#get-notifications)
* [Mark Notifications as Read](../../doc/controllers/notifications.md#mark-notifications-as-read)


# Get Notifications

```java
CompletableFuture<ApiResponse<NotificationsJsonResponse>> getNotificationsAsync()
```

## Response Type

**200**: notifications

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`NotificationsJsonResponse`](../../doc/models/notifications-json-response.md).

## Example Usage

```java
notificationsApi.getNotificationsAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Mark Notifications as Read

```java
CompletableFuture<ApiResponse<NotificationsMarkReadJsonResponse>> markNotificationsAsReadAsync(
    final NotificationsMarkReadJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`NotificationsMarkReadJsonRequest`](../../doc/models/notifications-mark-read-json-request.md) | Body, Optional | - |

## Response Type

**200**: notifications marked read

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`NotificationsMarkReadJsonResponse`](../../doc/models/notifications-mark-read-json-response.md).

## Example Usage

```java
notificationsApi.markNotificationsAsReadAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

