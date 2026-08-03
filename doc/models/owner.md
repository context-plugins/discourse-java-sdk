
# Owner

## Structure

`Owner`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `LastPostedAt` | `String` | Required | - | String getLastPostedAt() | setLastPostedAt(String lastPostedAt) |
| `LastSeenAt` | `String` | Required | - | String getLastSeenAt() | setLastSeenAt(String lastSeenAt) |
| `AddedAt` | `String` | Required | - | String getAddedAt() | setAddedAt(String addedAt) |
| `Timezone` | `String` | Required | - | String getTimezone() | setTimezone(String timezone) |

## Example

```java
import com.example.discourse.models.Owner;

Owner owner = new Owner.Builder(
    84,
    "username6",
    "name4",
    "avatar_template6",
    "title0",
    "last_posted_at4",
    "last_seen_at0",
    "added_at0",
    "timezone6"
)
.build();
```

