
# Member

## Structure

`Member`

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
import com.example.discourse.models.Member;

Member member = new Member.Builder(
    196,
    "username4",
    "name6",
    "avatar_template4",
    "title8",
    "last_posted_at2",
    "last_seen_at2",
    "added_at8",
    "timezone4"
)
.build();
```

