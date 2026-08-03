
# User 11

## Structure

`User11`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |

## Example

```java
import com.example.discourse.models.User11;

User11 user11 = new User11.Builder(
    106,
    "username6",
    "name6",
    "avatar_template4",
    "title2"
)
.build();
```

