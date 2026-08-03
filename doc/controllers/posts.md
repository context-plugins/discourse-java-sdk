# Posts

```java
PostsApi postsApi = client.getPostsApi();
```

## Class Name

`PostsApi`

## Methods

* [List Posts](../../doc/controllers/posts.md#list-posts)
* [Create Topic Post PM](../../doc/controllers/posts.md#create-topic-post-pm)
* [Get Post](../../doc/controllers/posts.md#get-post)
* [Update Post](../../doc/controllers/posts.md#update-post)
* [Delete Post](../../doc/controllers/posts.md#delete-post)
* [Post Replies](../../doc/controllers/posts.md#post-replies)
* [Lock Post](../../doc/controllers/posts.md#lock-post)
* [Perform Post Action](../../doc/controllers/posts.md#perform-post-action)


# List Posts

```java
CompletableFuture<ApiResponse<PostsJsonResponse>> listPostsAsync(
    final Integer before)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `before` | `Integer` | Query, Optional | Load posts with an id lower than this value. Useful for pagination. |

## Response Type

**200**: latest posts

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`PostsJsonResponse`](../../doc/models/posts-json-response.md).

## Example Usage

```java
postsApi.listPostsAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Create Topic Post PM

```java
CompletableFuture<ApiResponse<PostsJsonResponse1>> createTopicPostPmAsync(
    final String apiKey,
    final String apiUsername,
    final PostsJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `body` | [`PostsJsonRequest`](../../doc/models/posts-json-request.md) | Body, Optional | - |

## Response Type

**200**: post created

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`PostsJsonResponse1`](../../doc/models/posts-json-response-1.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
PostsJsonRequest body = new PostsJsonRequest.Builder(
    "raw0"
)
.targetRecipients("blake,sam")
.archetype("private_message")
.build();

postsApi.createTopicPostPmAsync(apiKey, apiUsername, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Post

This endpoint can be used to get the number of likes on a post using the
`actions_summary` property in the response. `actions_summary` responses
with the id of `2` signify a `like`. If there are no `actions_summary`
items with the id of `2`, that means there are 0 likes. Other ids likely
refer to various different flag types.

```java
CompletableFuture<ApiResponse<PostsJsonResponse2>> getPostAsync(
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Template, Required | - |

## Response Type

**200**: single reviewable post

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`PostsJsonResponse2`](../../doc/models/posts-json-response-2.md).

## Example Usage

```java
String id = "id0";

postsApi.getPostAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Post

```java
CompletableFuture<ApiResponse<PostsJsonResponse3>> updatePostAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final PostsJsonRequest1 body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`PostsJsonRequest1`](../../doc/models/posts-json-request-1.md) | Body, Optional | - |

## Response Type

**200**: post updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`PostsJsonResponse3`](../../doc/models/posts-json-response-3.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
postsApi.updatePostAsync(apiKey, apiUsername, id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Delete Post

```java
CompletableFuture<ApiResponse<Void>> deletePostAsync(
    final String apiKey,
    final String apiUsername,
    final int id,
    final PostsJsonRequest2 body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `int` | Template, Required | - |
| `body` | [`PostsJsonRequest2`](../../doc/models/posts-json-request-2.md) | Body, Optional | - |

## Response Type

**200**: success response

`void`

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
int id = 112;
PostsJsonRequest2 body = new PostsJsonRequest2.Builder()
    .forceDestroy(true)
    .build();

postsApi.deletePostAsync(apiKey, apiUsername, id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Post Replies

```java
CompletableFuture<ApiResponse<List<PostsRepliesJsonResponse>>> postRepliesAsync(
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Template, Required | - |

## Response Type

**200**: post replies

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`List<PostsRepliesJsonResponse>`](../../doc/models/posts-replies-json-response.md).

## Example Usage

```java
String id = "id0";

postsApi.postRepliesAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Lock Post

```java
CompletableFuture<ApiResponse<PostsLockedJsonResponse>> lockPostAsync(
    final String apiKey,
    final String apiUsername,
    final String id,
    final PostsLockedJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `id` | `String` | Template, Required | - |
| `body` | [`PostsLockedJsonRequest`](../../doc/models/posts-locked-json-request.md) | Body, Optional | - |

## Response Type

**200**: post updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`PostsLockedJsonResponse`](../../doc/models/posts-locked-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String id = "id0";
postsApi.lockPostAsync(apiKey, apiUsername, id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Perform Post Action

```java
CompletableFuture<ApiResponse<PostActionsJsonResponse>> performPostActionAsync(
    final String apiKey,
    final String apiUsername,
    final PostActionsJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `body` | [`PostActionsJsonRequest`](../../doc/models/post-actions-json-request.md) | Body, Optional | - |

## Response Type

**200**: post updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`PostActionsJsonResponse`](../../doc/models/post-actions-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
postsApi.performPostActionAsync(apiKey, apiUsername, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

