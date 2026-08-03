
# Admin Users Anonymize Json Response

## Structure

`AdminUsersAnonymizeJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |

## Example

```java
import com.example.discourse.models.AdminUsersAnonymizeJsonResponse;

AdminUsersAnonymizeJsonResponse adminUsersAnonymizeJsonResponse = new AdminUsersAnonymizeJsonResponse.Builder(
    "success8",
    "username2"
)
.build();
```

