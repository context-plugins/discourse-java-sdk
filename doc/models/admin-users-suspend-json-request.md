
# Admin Users Suspend Json Request

## Structure

`AdminUsersSuspendJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `SuspendUntil` | `String` | Required | - | String getSuspendUntil() | setSuspendUntil(String suspendUntil) |
| `Reason` | `String` | Required | - | String getReason() | setReason(String reason) |
| `Message` | `String` | Optional | Will send an email with this message when present | String getMessage() | setMessage(String message) |
| `PostAction` | `String` | Optional | - | String getPostAction() | setPostAction(String postAction) |

## Example

```java
import com.example.discourse.models.AdminUsersSuspendJsonRequest;

AdminUsersSuspendJsonRequest adminUsersSuspendJsonRequest = new AdminUsersSuspendJsonRequest.Builder(
    "2121-02-22",
    "reason8"
)
.message("message6")
.postAction("delete")
.build();
```

