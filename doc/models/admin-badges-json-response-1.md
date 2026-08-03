
# Admin Badges Json Response 1

## Structure

`AdminBadgesJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `BadgeTypes` | [`List<BadgeType>`](../../doc/models/badge-type.md) | Required | - | List<BadgeType> getBadgeTypes() | setBadgeTypes(List<BadgeType> badgeTypes) |
| `Badge` | [`Badge1`](../../doc/models/badge-1.md) | Required | - | Badge1 getBadge() | setBadge(Badge1 badge) |

## Example

```java
import com.example.discourse.models.AdminBadgesJsonResponse1;
import com.example.discourse.models.Badge1;
import com.example.discourse.models.BadgeType;
import java.util.Arrays;

AdminBadgesJsonResponse1 adminBadgesJsonResponse1 = new AdminBadgesJsonResponse1.Builder(
    Arrays.asList(
        new BadgeType.Builder(
            206,
            "name0",
            172
        )
        .build()
    ),
    new Badge1.Builder(
        184,
        "name0",
        "description0",
        198,
        false,
        false,
        "icon2",
        "image_url6",
        56,
        false,
        false,
        192,
        false,
        "long_description2",
        "slug6",
        false,
        "query0",
        "trigger8",
        false,
        false,
        false,
        208,
        false
    )
    .build()
)
.build();
```

