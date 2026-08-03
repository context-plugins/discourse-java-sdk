
# Session Forgot Password Json Request

## Structure

`SessionForgotPasswordJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Login` | `String` | Required | - | String getLogin() | setLogin(String login) |

## Example

```java
import com.example.discourse.models.SessionForgotPasswordJsonRequest;

SessionForgotPasswordJsonRequest sessionForgotPasswordJsonRequest = new SessionForgotPasswordJsonRequest.Builder(
    "login8"
)
.build();
```

