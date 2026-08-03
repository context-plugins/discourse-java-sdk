
# Granted By

## Structure

`GrantedBy`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `FlairName` | `String` | Required | - | String getFlairName() | setFlairName(String flairName) |
| `Admin` | `boolean` | Required | - | boolean getAdmin() | setAdmin(boolean admin) |
| `Moderator` | `boolean` | Required | - | boolean getModerator() | setModerator(boolean moderator) |
| `TrustLevel` | `int` | Required | - | int getTrustLevel() | setTrustLevel(int trustLevel) |

## Example

```java
import com.example.discourse.models.GrantedBy;

GrantedBy grantedBy = new GrantedBy.Builder(
    130,
    "username0",
    "name0",
    "avatar_template0",
    "flair_name6",
    false,
    false,
    142
)
.build();
```

