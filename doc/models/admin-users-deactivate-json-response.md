
# Admin Users Deactivate Json Response

## Structure

`AdminUsersDeactivateJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |

## Example

```java
import com.example.discourse.models.AdminUsersDeactivateJsonResponse;

AdminUsersDeactivateJsonResponse adminUsersDeactivateJsonResponse = new AdminUsersDeactivateJsonResponse.Builder(
    "OK"
)
.build();
```

