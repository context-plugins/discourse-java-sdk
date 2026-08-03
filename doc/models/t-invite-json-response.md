
# T Invite Json Response

*This model accepts additional fields of type Object.*

## Structure

`TInviteJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `User` | [`User1`](../../doc/models/user-1.md) | Optional | - | User1 getUser() | setUser(User1 user) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TInviteJsonResponse;
import com.example.discourse.models.User1;
import java.io.IOException;

TInviteJsonResponse tInviteJsonResponse = new TInviteJsonResponse.Builder()
    .user(new User1.Builder()
        .id(76)
        .username("username0")
        .name("name0")
        .avatarTemplate("avatar_template0")
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

