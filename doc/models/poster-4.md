
# Poster 4

## Structure

`Poster4`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Extras` | `String` | Required | - | String getExtras() | setExtras(String extras) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `User` | [`User`](../../doc/models/user.md) | Required | - | User getUser() | setUser(User user) |

## Example

```java
import com.example.discourse.models.Poster4;
import com.example.discourse.models.User;

Poster4 poster4 = new Poster4.Builder(
    "extras4",
    "description0",
    new User.Builder(
        76,
        "username0",
        "name0",
        "avatar_template0"
    )
    .build()
)
.build();
```

