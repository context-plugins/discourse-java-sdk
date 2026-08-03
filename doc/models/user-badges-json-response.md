
# User Badges Json Response

## Structure

`UserBadgesJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Badges` | [`List<Badge3>`](../../doc/models/badge-3.md) | Optional | - | List<Badge3> getBadges() | setBadges(List<Badge3> badges) |
| `BadgeTypes` | [`List<BadgeType>`](../../doc/models/badge-type.md) | Optional | - | List<BadgeType> getBadgeTypes() | setBadgeTypes(List<BadgeType> badgeTypes) |
| `GrantedBies` | [`List<GrantedBy>`](../../doc/models/granted-by.md) | Optional | - | List<GrantedBy> getGrantedBies() | setGrantedBies(List<GrantedBy> grantedBies) |
| `UserBadges` | [`List<UserBadge>`](../../doc/models/user-badge.md) | Required | - | List<UserBadge> getUserBadges() | setUserBadges(List<UserBadge> userBadges) |

## Example

```java
import com.example.discourse.models.Badge3;
import com.example.discourse.models.BadgeType;
import com.example.discourse.models.GrantedBy;
import com.example.discourse.models.UserBadge;
import com.example.discourse.models.UserBadgesJsonResponse;
import java.util.Arrays;

UserBadgesJsonResponse userBadgesJsonResponse = new UserBadgesJsonResponse.Builder(
    Arrays.asList(
        new UserBadge.Builder(
            222,
            "granted_at8",
            130,
            "is_favorite8",
            false,
            182,
            28
        )
        .build()
    )
)
.badges(Arrays.asList(
        new Badge3.Builder(
            68,
            "name0",
            "description0",
            82,
            false,
            false,
            "icon8",
            "image_url6",
            false,
            false,
            52,
            false,
            "slug6",
            false,
            92
        )
        .build(),
        new Badge3.Builder(
            68,
            "name0",
            "description0",
            82,
            false,
            false,
            "icon8",
            "image_url6",
            false,
            false,
            52,
            false,
            "slug6",
            false,
            92
        )
        .build()
    ))
.badgeTypes(Arrays.asList(
        new BadgeType.Builder(
            206,
            "name0",
            172
        )
        .build(),
        new BadgeType.Builder(
            206,
            "name0",
            172
        )
        .build()
    ))
.grantedBies(Arrays.asList(
        new GrantedBy.Builder(
            198,
            "username6",
            "name6",
            "avatar_template6",
            "flair_name0",
            false,
            false,
            182
        )
        .build(),
        new GrantedBy.Builder(
            198,
            "username6",
            "name6",
            "avatar_template6",
            "flair_name0",
            false,
            false,
            182
        )
        .build()
    ))
.build();
```

