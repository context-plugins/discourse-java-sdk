# Topics

```java
TopicsApi topicsApi = client.getTopicsApi();
```

## Class Name

`TopicsApi`

## Methods

* [Get Specific Posts from Topic](../../doc/controllers/topics.md#get-specific-posts-from-topic)
* [Get Topic](../../doc/controllers/topics.md#get-topic)
* [Remove Topic](../../doc/controllers/topics.md#remove-topic)
* [Update Topic](../../doc/controllers/topics.md#update-topic)
* [Invite to Topic](../../doc/controllers/topics.md#invite-to-topic)
* [Invite Group to Topic](../../doc/controllers/topics.md#invite-group-to-topic)
* [Bookmark Topic](../../doc/controllers/topics.md#bookmark-topic)
* [Update Topic Status](../../doc/controllers/topics.md#update-topic-status)
* [List Latest Topics](../../doc/controllers/topics.md#list-latest-topics)
* [List Top Topics](../../doc/controllers/topics.md#list-top-topics)
* [Set Notification Level](../../doc/controllers/topics.md#set-notification-level)
* [Update Topic Timestamp](../../doc/controllers/topics.md#update-topic-timestamp)
* [Create Topic Timer](../../doc/controllers/topics.md#create-topic-timer)
* [Get Topic by External Id](../../doc/controllers/topics.md#get-topic-by-external-id)


# Get Specific Posts from Topic

```java
CompletableFuture<ApiResponse<TPostsJsonResponse>> getSpecificPostsFromTopicAsync(
    final String apiKey,
    final String apiUsername,
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |

## Response Type

**200**: specific posts

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TPostsJsonResponse`](../../doc/models/t-posts-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";

topicsApi.getSpecificPostsFromTopicAsync(apiKey, apiUsername, id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Topic

```java
CompletableFuture<ApiResponse<TJsonResponse>> getTopicAsync(
    final String apiKey,
    final String apiUsername,
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |

## Response Type

**200**: specific posts

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TJsonResponse`](../../doc/models/t-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";

topicsApi.getTopicAsync(apiKey, apiUsername, id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Remove Topic

```java
CompletableFuture<ApiResponse<Void>> removeTopicAsync(
    final String apiKey,
    final String apiUsername,
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |

## Response Type

**200**: specific posts

`void`

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";

topicsApi.removeTopicAsync(apiKey, apiUsername, id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Topic

```java
CompletableFuture<ApiResponse<TJsonResponse1>> updateTopicAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final TJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`TJsonRequest`](../../doc/models/t-json-request.md) | Body, Optional | - |

## Response Type

**200**: topic updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TJsonResponse1`](../../doc/models/t-json-response-1.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
topicsApi.updateTopicAsync(apiKey, apiUsername, id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Invite to Topic

```java
CompletableFuture<ApiResponse<TInviteJsonResponse>> inviteToTopicAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final TInviteJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`TInviteJsonRequest`](../../doc/models/t-invite-json-request.md) | Body, Optional | - |

## Response Type

**200**: topic updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TInviteJsonResponse`](../../doc/models/t-invite-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
topicsApi.inviteToTopicAsync(apiKey, apiUsername, id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Invite Group to Topic

```java
CompletableFuture<ApiResponse<TInviteGroupJsonResponse>> inviteGroupToTopicAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final TInviteGroupJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`TInviteGroupJsonRequest`](../../doc/models/t-invite-group-json-request.md) | Body, Optional | - |

## Response Type

**200**: invites to a PM

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TInviteGroupJsonResponse`](../../doc/models/t-invite-group-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
topicsApi.inviteGroupToTopicAsync(apiKey, apiUsername, id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Bookmark Topic

```java
CompletableFuture<ApiResponse<Void>> bookmarkTopicAsync(
    final String apiKey,
    final String apiUsername,
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |

## Response Type

**200**: topic updated

`void`

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";

topicsApi.bookmarkTopicAsync(apiKey, apiUsername, id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Topic Status

```java
CompletableFuture<ApiResponse<TStatusJsonResponse>> updateTopicStatusAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final TStatusJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`TStatusJsonRequest`](../../doc/models/t-status-json-request.md) | Body, Optional | - |

## Response Type

**200**: topic updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TStatusJsonResponse`](../../doc/models/t-status-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
TStatusJsonRequest body = new TStatusJsonRequest.Builder(
    Status1.PINNED_GLOBALLY,
    Enabled.ENUM_TRUE
)
.until("2030-12-31")
.build();

topicsApi.updateTopicStatusAsync(apiKey, apiUsername, id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Latest Topics

```java
CompletableFuture<ApiResponse<LatestJsonResponse>> listLatestTopicsAsync(
    final String apiKey,
    final String apiUsername,
    final String order,
    final String ascending,
    final Integer perPage)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `order` | `String` | Query, Optional | Enum: `default`, `created`, `activity`, `views`, `posts`, `category`,<br>`likes`, `op_likes`, `posters` |
| `ascending` | `String` | Query, Optional | Defaults to `desc`, add `ascending=true` to sort asc |
| `perPage` | `Integer` | Query, Optional | Maximum number of topics returned, between 1-100 |

## Response Type

**200**: topic updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`LatestJsonResponse`](../../doc/models/latest-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";

topicsApi.listLatestTopicsAsync(apiKey, apiUsername, null, null, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Top Topics

```java
CompletableFuture<ApiResponse<TopJsonResponse>> listTopTopicsAsync(
    final String apiKey,
    final String apiUsername,
    final String period,
    final Integer perPage)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `period` | `String` | Query, Optional | Enum: `all`, `yearly`, `quarterly`, `monthly`, `weekly`, `daily` |
| `perPage` | `Integer` | Query, Optional | Maximum number of topics returned, between 1-100 |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TopJsonResponse`](../../doc/models/top-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";

topicsApi.listTopTopicsAsync(apiKey, apiUsername, null, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Set Notification Level

```java
CompletableFuture<ApiResponse<TNotificationsJsonResponse>> setNotificationLevelAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final TNotificationsJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`TNotificationsJsonRequest`](../../doc/models/t-notifications-json-request.md) | Body, Optional | - |

## Response Type

**200**: topic updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TNotificationsJsonResponse`](../../doc/models/t-notifications-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
topicsApi.setNotificationLevelAsync(apiKey, apiUsername, id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Topic Timestamp

```java
CompletableFuture<ApiResponse<TChangeTimestampJsonResponse>> updateTopicTimestampAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final TChangeTimestampJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`TChangeTimestampJsonRequest`](../../doc/models/t-change-timestamp-json-request.md) | Body, Optional | - |

## Response Type

**200**: topic updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TChangeTimestampJsonResponse`](../../doc/models/t-change-timestamp-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
TChangeTimestampJsonRequest body = new TChangeTimestampJsonRequest.Builder(
    "1594291380"
)
.build();

topicsApi.updateTopicTimestampAsync(apiKey, apiUsername, id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Create Topic Timer

```java
CompletableFuture<ApiResponse<TTimerJsonResponse>> createTopicTimerAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final TTimerJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`TTimerJsonRequest`](../../doc/models/t-timer-json-request.md) | Body, Optional | - |

## Response Type

**200**: topic updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TTimerJsonResponse`](../../doc/models/t-timer-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
topicsApi.createTopicTimerAsync(apiKey, apiUsername, id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Topic by External Id

```java
CompletableFuture<ApiResponse<Void>> getTopicByExternalIdAsync(
    final String externalId)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `externalId` | `String` | Template, Required | - |

## Response Type

**200**

`void`

## Example Usage

```java
String externalId = "external_id6";

topicsApi.getTopicByExternalIdAsync(externalId).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

