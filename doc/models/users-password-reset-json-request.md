
# Users Password Reset Json Request

## Structure

`UsersPasswordResetJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Password` | `String` | Required | - | String getPassword() | setPassword(String password) |

## Example

```java
import com.example.discourse.models.UsersPasswordResetJsonRequest;

UsersPasswordResetJsonRequest usersPasswordResetJsonRequest = new UsersPasswordResetJsonRequest.Builder(
    "username6",
    "password0"
)
.build();
```

