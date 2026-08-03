
# Last Poster

## Structure

`LastPoster`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |

## Example

```java
import com.example.discourse.models.LastPoster;

LastPoster lastPoster = new LastPoster.Builder(
    94,
    "username8",
    "name8",
    "avatar_template2"
)
.build();
```

