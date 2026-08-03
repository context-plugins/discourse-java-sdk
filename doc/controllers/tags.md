# Tags

```java
TagsApi tagsApi = client.getTagsApi();
```

## Class Name

`TagsApi`

## Methods

* [List Tag Groups](../../doc/controllers/tags.md#list-tag-groups)
* [Create Tag Group](../../doc/controllers/tags.md#create-tag-group)
* [Get Tag Group](../../doc/controllers/tags.md#get-tag-group)
* [Update Tag Group](../../doc/controllers/tags.md#update-tag-group)
* [List Tags](../../doc/controllers/tags.md#list-tags)
* [Get Tag](../../doc/controllers/tags.md#get-tag)


# List Tag Groups

```java
CompletableFuture<ApiResponse<TagGroupsJsonResponse>> listTagGroupsAsync()
```

## Response Type

**200**: tags

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TagGroupsJsonResponse`](../../doc/models/tag-groups-json-response.md).

## Example Usage

```java
tagsApi.listTagGroupsAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Create Tag Group

```java
CompletableFuture<ApiResponse<TagGroupsJsonResponse1>> createTagGroupAsync(
    final TagGroupsJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`TagGroupsJsonRequest`](../../doc/models/tag-groups-json-request.md) | Body, Optional | - |

## Response Type

**200**: tag group created

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TagGroupsJsonResponse1`](../../doc/models/tag-groups-json-response-1.md).

## Example Usage

```java
tagsApi.createTagGroupAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Tag Group

```java
CompletableFuture<ApiResponse<TagGroupsJsonResponse2>> getTagGroupAsync(
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Template, Required | - |

## Response Type

**200**: notifications

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TagGroupsJsonResponse2`](../../doc/models/tag-groups-json-response-2.md).

## Example Usage

```java
String id = "id0";

tagsApi.getTagGroupAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Tag Group

```java
CompletableFuture<ApiResponse<TagGroupsJsonResponse3>> updateTagGroupAsync(
    final String id,
    final TagGroupsJsonRequest1 body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Template, Required | - |
| `body` | [`TagGroupsJsonRequest1`](../../doc/models/tag-groups-json-request-1.md) | Body, Optional | - |

## Response Type

**200**: Tag group updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TagGroupsJsonResponse3`](../../doc/models/tag-groups-json-response-3.md).

## Example Usage

```java
String id = "id0";
tagsApi.updateTagGroupAsync(id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Tags

```java
CompletableFuture<ApiResponse<TagsJsonResponse>> listTagsAsync()
```

## Response Type

**200**: notifications

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TagsJsonResponse`](../../doc/models/tags-json-response.md).

## Example Usage

```java
tagsApi.listTagsAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Tag

```java
CompletableFuture<ApiResponse<TagJsonResponse>> getTagAsync(
    final String name)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `name` | `String` | Template, Required | - |

## Response Type

**200**: notifications

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`TagJsonResponse`](../../doc/models/tag-json-response.md).

## Example Usage

```java
String name = "name0";

tagsApi.getTagAsync(name).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

