# Groups

```java
GroupsApi groupsApi = client.getGroupsApi();
```

## Class Name

`GroupsApi`

## Methods

* [Create Group](../../doc/controllers/groups.md#create-group)
* [Delete Group](../../doc/controllers/groups.md#delete-group)
* [Get Group](../../doc/controllers/groups.md#get-group)
* [Update Group](../../doc/controllers/groups.md#update-group)
* [Get Group by Id](../../doc/controllers/groups.md#get-group-by-id)
* [List Group Members](../../doc/controllers/groups.md#list-group-members)
* [Add Group Members](../../doc/controllers/groups.md#add-group-members)
* [Remove Group Members](../../doc/controllers/groups.md#remove-group-members)
* [List Groups](../../doc/controllers/groups.md#list-groups)


# Create Group

```java
CompletableFuture<ApiResponse<AdminGroupsJsonResponse>> createGroupAsync(
    final AdminGroupsJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`AdminGroupsJsonRequest`](../../doc/models/admin-groups-json-request.md) | Body, Optional | - |

## Response Type

**200**: group created

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminGroupsJsonResponse`](../../doc/models/admin-groups-json-response.md).

## Example Usage

```java
groupsApi.createGroupAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Delete Group

```java
CompletableFuture<ApiResponse<AdminGroupsJsonResponse1>> deleteGroupAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminGroupsJsonResponse1`](../../doc/models/admin-groups-json-response-1.md).

## Example Usage

```java
int id = 112;

groupsApi.deleteGroupAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Group

```java
CompletableFuture<ApiResponse<GroupsJsonResponse>> getGroupAsync(
    final String name)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `name` | `String` | Template, Required | Use group name instead of id |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`GroupsJsonResponse`](../../doc/models/groups-json-response.md).

## Example Usage

```java
String name = "name";

groupsApi.getGroupAsync(name).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Group

```java
CompletableFuture<ApiResponse<GroupsJsonResponse1>> updateGroupAsync(
    final int id,
    final GroupsJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`GroupsJsonRequest`](../../doc/models/groups-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`GroupsJsonResponse1`](../../doc/models/groups-json-response-1.md).

## Example Usage

```java
int id = 112;
groupsApi.updateGroupAsync(id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get Group by Id

```java
CompletableFuture<ApiResponse<GroupsByIdJsonResponse>> getGroupByIdAsync(
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Template, Required | Use group name instead of id |

## Response Type

**200**: success response (by id)

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`GroupsByIdJsonResponse`](../../doc/models/groups-by-id-json-response.md).

## Example Usage

```java
String id = "name";

groupsApi.getGroupByIdAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Group Members

```java
CompletableFuture<ApiResponse<GroupsMembersJsonResponse>> listGroupMembersAsync(
    final String name)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `name` | `String` | Template, Required | Use group name instead of id |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`GroupsMembersJsonResponse`](../../doc/models/groups-members-json-response.md).

## Example Usage

```java
String name = "name";

groupsApi.listGroupMembersAsync(name).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Add Group Members

```java
CompletableFuture<ApiResponse<GroupsMembersJsonResponse1>> addGroupMembersAsync(
    final int id,
    final GroupsMembersJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`GroupsMembersJsonRequest`](../../doc/models/groups-members-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`GroupsMembersJsonResponse1`](../../doc/models/groups-members-json-response-1.md).

## Example Usage

```java
int id = 112;
GroupsMembersJsonRequest body = new GroupsMembersJsonRequest.Builder()
    .usernames("username1,username2")
    .build();

groupsApi.addGroupMembersAsync(id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Remove Group Members

```java
CompletableFuture<ApiResponse<GroupsMembersJsonResponse2>> removeGroupMembersAsync(
    final int id,
    final GroupsMembersJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`GroupsMembersJsonRequest`](../../doc/models/groups-members-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`GroupsMembersJsonResponse2`](../../doc/models/groups-members-json-response-2.md).

## Example Usage

```java
int id = 112;
GroupsMembersJsonRequest body = new GroupsMembersJsonRequest.Builder()
    .usernames("username1,username2")
    .build();

groupsApi.removeGroupMembersAsync(id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Groups

```java
CompletableFuture<ApiResponse<GroupsJsonResponse2>> listGroupsAsync()
```

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`GroupsJsonResponse2`](../../doc/models/groups-json-response-2.md).

## Example Usage

```java
groupsApi.listGroupsAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

