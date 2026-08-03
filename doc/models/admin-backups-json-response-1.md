
# Admin Backups Json Response 1

## Structure

`AdminBackupsJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |

## Example

```java
import com.example.discourse.models.AdminBackupsJsonResponse1;

AdminBackupsJsonResponse1 adminBackupsJsonResponse1 = new AdminBackupsJsonResponse1.Builder(
    "OK"
)
.build();
```

