# Categories

```java
CategoriesApi categoriesApi = client.getCategoriesApi();
```

## Class Name

`CategoriesApi`

## Methods

* [Create Category](../../doc/controllers/categories.md#create-category)
* [List Categories](../../doc/controllers/categories.md#list-categories)
* [Update Category](../../doc/controllers/categories.md#update-category)
* [List Category Topics](../../doc/controllers/categories.md#list-category-topics)
* [Get Category](../../doc/controllers/categories.md#get-category)


# Create Category

```java
CompletableFuture<ApiResponse<CategoriesJsonResponse>> createCategoryAsync(
    final CategoriesJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`CategoriesJsonRequest`](../../doc/models/categories-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`CategoriesJsonResponse`](../../doc/models/categories-json-response.md).

## Example Usage

```java
CategoriesJsonRequest body = new CategoriesJsonRequest.Builder(
    "name6"
)
.color("49d9e9")
.textColor("f0fcfd")
.build();

categoriesApi.createCategoryAsync(body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Categories

```java
CompletableFuture<ApiResponse<CategoriesJsonResponse1>> listCategoriesAsync(
    final Boolean includeSubcategories)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `includeSubcategories` | `Boolean` | Query, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`CategoriesJsonResponse1`](../../doc/models/categories-json-response-1.md).

## Example Usage

```java
categoriesApi.listCategoriesAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Category

```java
CompletableFuture<ApiResponse<CategoriesJsonResponse2>> updateCategoryAsync(
    final int id,
    final CategoriesJsonRequest1 body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`CategoriesJsonRequest1`](../../doc/models/categories-json-request-1.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`CategoriesJsonResponse2`](../../doc/models/categories-json-response-2.md).

## Example Usage

```java
int id = 112;
CategoriesJsonRequest1 body = new CategoriesJsonRequest1.Builder(
    "name6"
)
.color("49d9e9")
.textColor("f0fcfd")
.build();

categoriesApi.updateCategoryAsync(id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Category Topics

```java
CompletableFuture<ApiResponse<CJsonResponse>> listCategoryTopicsAsync(
    final String slug,
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `slug` | `String` | Template, Required | - |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`CJsonResponse`](../../doc/models/c-json-response.md).

## Example Usage

```java
String slug = "slug6";
int id = 112;

categoriesApi.listCategoryTopicsAsync(slug, id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Category

```java
CompletableFuture<ApiResponse<CShowJsonResponse>> getCategoryAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`CShowJsonResponse`](../../doc/models/c-show-json-response.md).

## Example Usage

```java
int id = 112;

categoriesApi.getCategoryAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

