# Private Messages

```java
PrivateMessagesApi privateMessagesApi = client.getPrivateMessagesApi();
```

## Class Name

`PrivateMessagesApi`

## Methods

* [List User Private Messages](../../doc/controllers/private-messages.md#list-user-private-messages)
* [Get User Sent Private Messages](../../doc/controllers/private-messages.md#get-user-sent-private-messages)


# List User Private Messages

```java
CompletableFuture<ApiResponse<TopicsPrivateMessagesJsonResponse>> listUserPrivateMessagesAsync(
    final String username)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |

## Response Type

**200**: private messages

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TopicsPrivateMessagesJsonResponse`](../../doc/models/topics-private-messages-json-response.md).

## Example Usage

```java
String username = "username0";

privateMessagesApi.listUserPrivateMessagesAsync(username).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get User Sent Private Messages

```java
CompletableFuture<ApiResponse<TopicsPrivateMessagesSentJsonResponse>> getUserSentPrivateMessagesAsync(
    final String username)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |

## Response Type

**200**: private messages

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TopicsPrivateMessagesSentJsonResponse`](../../doc/models/topics-private-messages-sent-json-response.md).

## Example Usage

```java
String username = "username0";

privateMessagesApi.getUserSentPrivateMessagesAsync(username).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

