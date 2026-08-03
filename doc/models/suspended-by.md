
# Suspended By

## Structure

`SuspendedBy`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |

## Example

```java
import com.example.discourse.models.SuspendedBy;

SuspendedBy suspendedBy = new SuspendedBy.Builder(
    102,
    "username8",
    "name2",
    "avatar_template8"
)
.build();
```

