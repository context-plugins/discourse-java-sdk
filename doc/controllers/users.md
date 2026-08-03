# Users

```java
UsersApi usersApi = client.getUsersApi();
```

## Class Name

`UsersApi`

## Methods

* [Create User](../../doc/controllers/users.md#create-user)
* [Get User](../../doc/controllers/users.md#get-user)
* [Update User](../../doc/controllers/users.md#update-user)
* [Get User External Id](../../doc/controllers/users.md#get-user-external-id)
* [Get User Identiy Provider External Id](../../doc/controllers/users.md#get-user-identiy-provider-external-id)
* [Update Avatar](../../doc/controllers/users.md#update-avatar)
* [Update Email](../../doc/controllers/users.md#update-email)
* [Update Username](../../doc/controllers/users.md#update-username)
* [List Users Public](../../doc/controllers/users.md#list-users-public)
* [Admin Get User](../../doc/controllers/users.md#admin-get-user)
* [Delete User](../../doc/controllers/users.md#delete-user)
* [Activate User](../../doc/controllers/users.md#activate-user)
* [Deactivate User](../../doc/controllers/users.md#deactivate-user)
* [Suspend User](../../doc/controllers/users.md#suspend-user)
* [Silence User](../../doc/controllers/users.md#silence-user)
* [Anonymize User](../../doc/controllers/users.md#anonymize-user)
* [Log Out User](../../doc/controllers/users.md#log-out-user)
* [Refresh Gravatar](../../doc/controllers/users.md#refresh-gravatar)
* [Admin List Users](../../doc/controllers/users.md#admin-list-users)
* [Admin List Users Flag](../../doc/controllers/users.md#admin-list-users-flag)
* [List User Actions](../../doc/controllers/users.md#list-user-actions)
* [Send Password Reset Email](../../doc/controllers/users.md#send-password-reset-email)
* [Change Password](../../doc/controllers/users.md#change-password)
* [Get User Emails](../../doc/controllers/users.md#get-user-emails)


# Create User

```java
CompletableFuture<ApiResponse<UsersJsonResponse>> createUserAsync(
    final String apiKey,
    final String apiUsername,
    final UsersJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `body` | [`UsersJsonRequest`](../../doc/models/users-json-request.md) | Body, Optional | - |

## Response Type

**200**: user created

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UsersJsonResponse`](../../doc/models/users-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
usersApi.createUserAsync(apiKey, apiUsername, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get User

```java
CompletableFuture<ApiResponse<UJsonResponse>> getUserAsync(
    final String apiKey,
    final String apiUsername,
    final String username)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `username` | `String` | Template, Required | - |

## Response Type

**200**: user with primary group response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UJsonResponse`](../../doc/models/u-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String username = "username0";

usersApi.getUserAsync(apiKey, apiUsername, username).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update User

```java
CompletableFuture<ApiResponse<UJsonResponse1>> updateUserAsync(
    final String apiKey,
    final String apiUsername,
    final String username,
    final UJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `username` | `String` | Template, Required | - |
| `body` | [`UJsonRequest`](../../doc/models/u-json-request.md) | Body, Optional | - |

## Response Type

**200**: user updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UJsonResponse1`](../../doc/models/u-json-response-1.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String username = "username0";
usersApi.updateUserAsync(apiKey, apiUsername, username, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get User External Id

```java
CompletableFuture<ApiResponse<UByExternalJsonResponse>> getUserExternalIdAsync(
    final String apiKey,
    final String apiUsername,
    final String externalId)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `externalId` | `String` | Template, Required | - |

## Response Type

**200**: user response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UByExternalJsonResponse`](../../doc/models/u-by-external-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String externalId = "external_id6";

usersApi.getUserExternalIdAsync(apiKey, apiUsername, externalId).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get User Identiy Provider External Id

```java
CompletableFuture<ApiResponse<UByExternalJsonResponse>> getUserIdentiyProviderExternalIdAsync(
    final String apiKey,
    final String apiUsername,
    final String provider,
    final String externalId)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `apiKey` | `String` | Header, Required | - |
| `apiUsername` | `String` | Header, Required | - |
| `provider` | `String` | Template, Required | Authentication provider name. Can be found in the provider callback<br>URL: `/auth/{provider}/callback` |
| `externalId` | `String` | Template, Required | - |

## Response Type

**200**: user response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UByExternalJsonResponse`](../../doc/models/u-by-external-json-response.md).

## Example Usage

```java
String apiKey = "Api-Key6";
String apiUsername = "Api-Username8";
String provider = "provider8";
String externalId = "external_id6";

usersApi.getUserIdentiyProviderExternalIdAsync(apiKey, apiUsername, provider, externalId).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Avatar

```java
CompletableFuture<ApiResponse<UPreferencesAvatarPickJsonResponse>> updateAvatarAsync(
    final String username,
    final UPreferencesAvatarPickJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |
| `body` | [`UPreferencesAvatarPickJsonRequest`](../../doc/models/u-preferences-avatar-pick-json-request.md) | Body, Optional | - |

## Response Type

**200**: avatar updated

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UPreferencesAvatarPickJsonResponse`](../../doc/models/u-preferences-avatar-pick-json-response.md).

## Example Usage

```java
String username = "username0";
usersApi.updateAvatarAsync(username, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Email

```java
CompletableFuture<ApiResponse<Void>> updateEmailAsync(
    final String username,
    final UPreferencesEmailJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |
| `body` | [`UPreferencesEmailJsonRequest`](../../doc/models/u-preferences-email-json-request.md) | Body, Optional | - |

## Response Type

**200**: email updated

`void`

## Example Usage

```java
String username = "username0";
usersApi.updateEmailAsync(username, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Update Username

```java
CompletableFuture<ApiResponse<Void>> updateUsernameAsync(
    final String username,
    final UPreferencesUsernameJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |
| `body` | [`UPreferencesUsernameJsonRequest`](../../doc/models/u-preferences-username-json-request.md) | Body, Optional | - |

## Response Type

**200**: username updated

`void`

## Example Usage

```java
String username = "username0";
usersApi.updateUsernameAsync(username, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List Users Public

```java
CompletableFuture<ApiResponse<DirectoryItemsJsonResponse>> listUsersPublicAsync(
    final Period1 period,
    final Order2 order,
    final Asc asc,
    final Integer page)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `period` | [`Period1`](../../doc/models/period-1.md) | Query, Required | - |
| `order` | [`Order2`](../../doc/models/order-2.md) | Query, Required | - |
| `asc` | [`Asc`](../../doc/models/asc.md) | Query, Optional | - |
| `page` | `Integer` | Query, Optional | - |

## Response Type

**200**: directory items response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`DirectoryItemsJsonResponse`](../../doc/models/directory-items-json-response.md).

## Example Usage

```java
Period1 period = Period1.YEARLY;
Order2 order = Order2.TOPICS_ENTERED;

usersApi.listUsersPublicAsync(period, order, null, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Admin Get User

```java
CompletableFuture<ApiResponse<AdminUsersJsonResponse>> adminGetUserAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersJsonResponse`](../../doc/models/admin-users-json-response.md).

## Example Usage

```java
int id = 112;

usersApi.adminGetUserAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Delete User

```java
CompletableFuture<ApiResponse<AdminUsersJsonResponse1>> deleteUserAsync(
    final int id,
    final AdminUsersJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`AdminUsersJsonRequest`](../../doc/models/admin-users-json-request.md) | Body, Optional | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersJsonResponse1`](../../doc/models/admin-users-json-response-1.md).

## Example Usage

```java
int id = 112;
usersApi.deleteUserAsync(id, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Activate User

```java
CompletableFuture<ApiResponse<AdminUsersActivateJsonResponse>> activateUserAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersActivateJsonResponse`](../../doc/models/admin-users-activate-json-response.md).

## Example Usage

```java
int id = 112;

usersApi.activateUserAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Deactivate User

```java
CompletableFuture<ApiResponse<AdminUsersDeactivateJsonResponse>> deactivateUserAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersDeactivateJsonResponse`](../../doc/models/admin-users-deactivate-json-response.md).

## Example Usage

```java
int id = 112;

usersApi.deactivateUserAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Suspend User

```java
CompletableFuture<ApiResponse<AdminUsersSuspendJsonResponse>> suspendUserAsync(
    final int id,
    final AdminUsersSuspendJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`AdminUsersSuspendJsonRequest`](../../doc/models/admin-users-suspend-json-request.md) | Body, Optional | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersSuspendJsonResponse`](../../doc/models/admin-users-suspend-json-response.md).

## Example Usage

```java
int id = 112;
AdminUsersSuspendJsonRequest body = new AdminUsersSuspendJsonRequest.Builder(
    "2121-02-22",
    "reason8"
)
.postAction("delete")
.build();

usersApi.suspendUserAsync(id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Silence User

```java
CompletableFuture<ApiResponse<AdminUsersSilenceJsonResponse>> silenceUserAsync(
    final int id,
    final AdminUsersSilenceJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |
| `body` | [`AdminUsersSilenceJsonRequest`](../../doc/models/admin-users-silence-json-request.md) | Body, Optional | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersSilenceJsonResponse`](../../doc/models/admin-users-silence-json-response.md).

## Example Usage

```java
int id = 112;
AdminUsersSilenceJsonRequest body = new AdminUsersSilenceJsonRequest.Builder(
    "06/01/2022 08:00:00",
    "reason8"
)
.postAction("delete")
.build();

usersApi.silenceUserAsync(id, body).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Anonymize User

```java
CompletableFuture<ApiResponse<AdminUsersAnonymizeJsonResponse>> anonymizeUserAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersAnonymizeJsonResponse`](../../doc/models/admin-users-anonymize-json-response.md).

## Example Usage

```java
int id = 112;

usersApi.anonymizeUserAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Log Out User

```java
CompletableFuture<ApiResponse<AdminUsersLogOutJsonResponse>> logOutUserAsync(
    final int id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `int` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminUsersLogOutJsonResponse`](../../doc/models/admin-users-log-out-json-response.md).

## Example Usage

```java
int id = 112;

usersApi.logOutUserAsync(id).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Refresh Gravatar

```java
CompletableFuture<ApiResponse<UserAvatarRefreshGravatarJsonResponse>> refreshGravatarAsync(
    final String username)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UserAvatarRefreshGravatarJsonResponse`](../../doc/models/user-avatar-refresh-gravatar-json-response.md).

## Example Usage

```java
String username = "username0";

usersApi.refreshGravatarAsync(username).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Admin List Users

```java
CompletableFuture<ApiResponse<List<AdminUsersJsonResponse2>>> adminListUsersAsync(
    final Order3 order,
    final Asc asc,
    final Integer page,
    final Boolean showEmails,
    final Boolean stats,
    final String email,
    final String ip)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `order` | [`Order3`](../../doc/models/order-3.md) | Query, Optional | - |
| `asc` | [`Asc`](../../doc/models/asc.md) | Query, Optional | - |
| `page` | `Integer` | Query, Optional | - |
| `showEmails` | `Boolean` | Query, Optional | Include user email addresses in response. These requests will<br>be logged in the staff action logs. |
| `stats` | `Boolean` | Query, Optional | Include user stats information |
| `email` | `String` | Query, Optional | Filter to the user with this email address |
| `ip` | `String` | Query, Optional | Filter to users with this IP address |

## Response Type

**200**: users response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`List<AdminUsersJsonResponse2>`](../../doc/models/admin-users-json-response-2.md).

## Example Usage

```java
usersApi.adminListUsersAsync(null, null, null, null, null, null, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Admin List Users Flag

```java
CompletableFuture<ApiResponse<List<AdminUsersListJsonResponse>>> adminListUsersFlagAsync(
    final Flag flag,
    final Order3 order,
    final Asc asc,
    final Integer page,
    final Boolean showEmails,
    final Boolean stats,
    final String email,
    final String ip)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `flag` | [`Flag`](../../doc/models/flag.md) | Template, Required | - |
| `order` | [`Order3`](../../doc/models/order-3.md) | Query, Optional | - |
| `asc` | [`Asc`](../../doc/models/asc.md) | Query, Optional | - |
| `page` | `Integer` | Query, Optional | - |
| `showEmails` | `Boolean` | Query, Optional | Include user email addresses in response. These requests will<br>be logged in the staff action logs. |
| `stats` | `Boolean` | Query, Optional | Include user stats information |
| `email` | `String` | Query, Optional | Filter to the user with this email address |
| `ip` | `String` | Query, Optional | Filter to users with this IP address |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`List<AdminUsersListJsonResponse>`](../../doc/models/admin-users-list-json-response.md).

## Example Usage

```java
Flag flag = Flag.STAFF;

usersApi.adminListUsersFlagAsync(flag, null, null, null, null, null, null, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# List User Actions

```java
CompletableFuture<ApiResponse<UserActionsJsonResponse>> listUserActionsAsync(
    final int offset,
    final String username,
    final String filter)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `offset` | `int` | Query, Required | - |
| `username` | `String` | Query, Required | - |
| `filter` | `String` | Query, Required | - |

## Response Type

**200**: response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UserActionsJsonResponse`](../../doc/models/user-actions-json-response.md).

## Example Usage

```java
int offset = 12;
String username = "username0";
String filter = "filter4";

usersApi.listUserActionsAsync(offset, username, filter).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Send Password Reset Email

```java
CompletableFuture<ApiResponse<SessionForgotPasswordJsonResponse>> sendPasswordResetEmailAsync(
    final SessionForgotPasswordJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`SessionForgotPasswordJsonRequest`](../../doc/models/session-forgot-password-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`SessionForgotPasswordJsonResponse`](../../doc/models/session-forgot-password-json-response.md).

## Example Usage

```java
usersApi.sendPasswordResetEmailAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Change Password

```java
CompletableFuture<ApiResponse<Void>> changePasswordAsync(
    final String token,
    final UsersPasswordResetJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `token` | `String` | Template, Required | - |
| `body` | [`UsersPasswordResetJsonRequest`](../../doc/models/users-password-reset-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

`void`

## Example Usage

```java
String token = "token6";
usersApi.changePasswordAsync(token, null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Get User Emails

```java
CompletableFuture<ApiResponse<UEmailsJsonResponse>> getUserEmailsAsync(
    final String username)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `username` | `String` | Template, Required | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`UEmailsJsonResponse`](../../doc/models/u-emails-json-response.md).

## Example Usage

```java
String username = "username0";

usersApi.getUserEmailsAsync(username).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

