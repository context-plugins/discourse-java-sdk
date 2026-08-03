
# User 2

*This model accepts additional fields of type Object.*

## Structure

`User2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Username` | `String` | Optional | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Optional | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.User2;
import java.io.IOException;

User2 user2 = new User2.Builder()
    .id(108)
    .username("username8")
    .name("name8")
    .avatarTemplate("avatar_template2")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

