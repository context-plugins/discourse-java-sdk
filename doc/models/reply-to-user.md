
# Reply to User

## Structure

`ReplyToUser`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |

## Example

```java
import com.example.discourse.models.ReplyToUser;

ReplyToUser replyToUser = new ReplyToUser.Builder(
    "username2",
    "avatar_template2"
)
.id(124)
.name("name8")
.build();
```

