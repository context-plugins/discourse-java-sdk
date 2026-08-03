
# Admin Backups Json Request

## Structure

`AdminBackupsJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `WithUploads` | `boolean` | Required | - | boolean getWithUploads() | setWithUploads(boolean withUploads) |

## Example

```java
import com.example.discourse.models.AdminBackupsJsonRequest;

AdminBackupsJsonRequest adminBackupsJsonRequest = new AdminBackupsJsonRequest.Builder(
    false
)
.build();
```

