
# Admin Badges Json Response

## Structure

`AdminBadgesJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Badges` | [`List<Badge>`](../../doc/models/badge.md) | Required | - | List<Badge> getBadges() | setBadges(List<Badge> badges) |
| `BadgeTypes` | [`List<BadgeType>`](../../doc/models/badge-type.md) | Required | - | List<BadgeType> getBadgeTypes() | setBadgeTypes(List<BadgeType> badgeTypes) |
| `BadgeGroupings` | [`List<BadgeGrouping>`](../../doc/models/badge-grouping.md) | Required | - | List<BadgeGrouping> getBadgeGroupings() | setBadgeGroupings(List<BadgeGrouping> badgeGroupings) |
| `AdminBadges` | [`AdminBadges`](../../doc/models/admin-badges.md) | Required | - | AdminBadges getAdminBadges() | setAdminBadges(AdminBadges adminBadges) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.AdminBadges;
import com.example.discourse.models.AdminBadgesJsonResponse;
import com.example.discourse.models.Badge;
import com.example.discourse.models.BadgeGrouping;
import com.example.discourse.models.BadgeType;
import com.example.discourse.models.Triggers;
import java.io.IOException;
import java.util.Arrays;

AdminBadgesJsonResponse adminBadgesJsonResponse = new AdminBadgesJsonResponse.Builder(
    Arrays.asList(
        new Badge.Builder(
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
            "long_description2",
            "slug6",
            false,
            "query0",
            158,
            false,
            false,
            false,
            172,
            92,
            false
        )
        .i18NName("i18n_name4")
        .build()
    ),
    Arrays.asList(
        new BadgeType.Builder(
            206,
            "name0",
            172
        )
        .build()
    ),
    Arrays.asList(
        new BadgeGrouping.Builder(
            40,
            "name8",
            "description8",
            70,
            false
        )
        .build()
    ),
    new AdminBadges.Builder(
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        new Triggers.Builder(
            26,
            198,
            74,
            164,
            132
        )
        .build(),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        )
    )
    .build()
)
.build();
```

