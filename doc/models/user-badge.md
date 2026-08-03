
# User Badge

## Structure

`UserBadge`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `GrantedAt` | `String` | Required | - | String getGrantedAt() | setGrantedAt(String grantedAt) |
| `GroupingPosition` | `int` | Required | - | int getGroupingPosition() | setGroupingPosition(int groupingPosition) |
| `IsFavorite` | `String` | Required | - | String getIsFavorite() | setIsFavorite(String isFavorite) |
| `CanFavorite` | `boolean` | Required | - | boolean getCanFavorite() | setCanFavorite(boolean canFavorite) |
| `BadgeId` | `int` | Required | - | int getBadgeId() | setBadgeId(int badgeId) |
| `GrantedById` | `int` | Required | - | int getGrantedById() | setGrantedById(int grantedById) |

## Example

```java
import com.example.discourse.models.UserBadge;

UserBadge userBadge = new UserBadge.Builder(
    182,
    "granted_at8",
    90,
    "is_favorite8",
    false,
    142,
    244
)
.build();
```

