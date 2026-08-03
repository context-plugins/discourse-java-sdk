# Invites

```java
InvitesApi invitesApi = client.getInvitesApi();
```

## Class Name

`InvitesApi`

## Methods

* [Create Invite](../../doc/controllers/invites.md#create-invite)
* [Create Multiple Invites](../../doc/controllers/invites.md#create-multiple-invites)


# Create Invite

```java
CompletableFuture<ApiResponse<InvitesJsonResponse>> createInviteAsync(
    final String apiKey,
    final String apiUsername,
    final InvitesJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `body` | [`InvitesJsonRequest`](../../doc/models/invites-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`InvitesJsonResponse`](../../doc/models/invites-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
InvitesJsonRequest body = new InvitesJsonRequest.Builder()
    .email("not-a-user-yet@example.com")
    .skipEmail(false)
    .maxRedemptionsAllowed(5)
    .groupIds("42,43")
    .groupNames("foo,bar")
    .build();

invitesApi.createInviteAsync(apiKey, apiUsername, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Create Multiple Invites

```java
CompletableFuture<ApiResponse<InvitesCreateMultipleJsonResponse>> createMultipleInvitesAsync(
    final String apiKey,
    final String apiUsername,
    final InvitesCreateMultipleJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `body` | [`InvitesCreateMultipleJsonRequest`](../../doc/models/invites-create-multiple-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`InvitesCreateMultipleJsonResponse`](../../doc/models/invites-create-multiple-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
InvitesCreateMultipleJsonRequest body = new InvitesCreateMultipleJsonRequest.Builder()
    .email("[\n  \"not-a-user-yet-1@example.com\",\n  \"not-a-user-yet-2@example.com\"\n]")
    .skipEmail(false)
    .maxRedemptionsAllowed(5)
    .groupIds("42,43")
    .groupNames("foo,bar")
    .build();

invitesApi.createMultipleInvitesAsync(apiKey, apiUsername, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

