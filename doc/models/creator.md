
# Creator

## Structure

`Creator`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |

## Example

```java
import com.example.discourse.models.Creator;

Creator creator = new Creator.Builder(
    76,
    "username2",
    "avatar_template2"
)
.name("name8")
.build();
```

