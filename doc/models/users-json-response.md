
# Users Json Response

## Structure

`UsersJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `boolean` | Required | - | boolean getSuccess() | setSuccess(boolean success) |
| `Active` | `boolean` | Required | - | boolean getActive() | setActive(boolean active) |
| `Message` | `String` | Required | - | String getMessage() | setMessage(String message) |
| `UserId` | `Integer` | Optional | - | Integer getUserId() | setUserId(Integer userId) |

## Example

```java
import com.example.discourse.models.UsersJsonResponse;

UsersJsonResponse usersJsonResponse = new UsersJsonResponse.Builder(
    false,
    false,
    "message0"
)
.userId(130)
.build();
```

