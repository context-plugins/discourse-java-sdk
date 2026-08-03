
# Admin Users Silence Json Request

## Structure

`AdminUsersSilenceJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `SilencedTill` | `String` | Required | - | String getSilencedTill() | setSilencedTill(String silencedTill) |
| `Reason` | `String` | Required | - | String getReason() | setReason(String reason) |
| `Message` | `String` | Optional | Will send an email with this message when present | String getMessage() | setMessage(String message) |
| `PostAction` | `String` | Optional | - | String getPostAction() | setPostAction(String postAction) |

## Example

```java
import com.example.discourse.models.AdminUsersSilenceJsonRequest;

AdminUsersSilenceJsonRequest adminUsersSilenceJsonRequest = new AdminUsersSilenceJsonRequest.Builder(
    "2022-06-01T08:00:00.000Z",
    "reason4"
)
.message("message0")
.postAction("delete")
.build();
```

