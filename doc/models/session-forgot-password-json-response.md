
# Session Forgot Password Json Response

## Structure

`SessionForgotPasswordJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |
| `UserFound` | `boolean` | Required | - | boolean getUserFound() | setUserFound(boolean userFound) |

## Example

```java
import com.example.discourse.models.SessionForgotPasswordJsonResponse;

SessionForgotPasswordJsonResponse sessionForgotPasswordJsonResponse = new SessionForgotPasswordJsonResponse.Builder(
    "success4",
    false
)
.build();
```

