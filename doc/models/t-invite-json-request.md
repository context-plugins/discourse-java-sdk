
# T Invite Json Request

*This model accepts additional fields of type Object.*

## Structure

`TInviteJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `User` | `String` | Optional | - | String getUser() | setUser(String user) |
| `Email` | `String` | Optional | - | String getEmail() | setEmail(String email) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TInviteJsonRequest;
import java.io.IOException;

TInviteJsonRequest tInviteJsonRequest = new TInviteJsonRequest.Builder()
    .user("user2")
    .email("email4")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

