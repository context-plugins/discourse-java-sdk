# Site

```java
SiteApi siteApi = client.getSiteApi();
```

## Class Name

`SiteApi`

## Methods

* [Get Site](../../doc/controllers/site.md#get-site)
* [Get Site Basic Info](../../doc/controllers/site.md#get-site-basic-info)


# Get Site

Can be used to fetch all categories and subcategories

```java
CompletableFuture<ApiResponse<SiteJsonResponse>> getSiteAsync()
```

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`SiteJsonResponse`](../../doc/models/site-json-response.md).

## Example Usage

```java
siteApi.getSiteAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Site Basic Info

Can be used to fetch basic info about a site

```java
CompletableFuture<ApiResponse<SiteBasicInfoJsonResponse>> getSiteBasicInfoAsync()
```

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`SiteBasicInfoJsonResponse`](../../doc/models/site-basic-info-json-response.md).

## Example Usage

```java
siteApi.getSiteBasicInfoAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

