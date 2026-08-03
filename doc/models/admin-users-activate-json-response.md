
# Admin Users Activate Json Response

## Structure

`AdminUsersActivateJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |

## Example

```java
import com.example.discourse.models.AdminUsersActivateJsonResponse;

AdminUsersActivateJsonResponse adminUsersActivateJsonResponse = new AdminUsersActivateJsonResponse.Builder(
    "OK"
)
.build();
```

