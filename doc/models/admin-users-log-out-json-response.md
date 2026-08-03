
# Admin Users Log Out Json Response

## Structure

`AdminUsersLogOutJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |

## Example

```java
import com.example.discourse.models.AdminUsersLogOutJsonResponse;

AdminUsersLogOutJsonResponse adminUsersLogOutJsonResponse = new AdminUsersLogOutJsonResponse.Builder(
    "OK"
)
.build();
```

