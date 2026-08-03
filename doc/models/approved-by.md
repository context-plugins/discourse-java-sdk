
# Approved By

## Structure

`ApprovedBy`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |

## Example

```java
import com.example.discourse.models.ApprovedBy;

ApprovedBy approvedBy = new ApprovedBy.Builder(
    156,
    "username4",
    "name6",
    "avatar_template4"
)
.build();
```

