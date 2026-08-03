
# Admin Badges

## Structure

`AdminBadges`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `ProtectedSystemFields` | `List<Object>` | Required | - | List<Object> getProtectedSystemFields() | setProtectedSystemFields(List<Object> protectedSystemFields) |
| `Triggers` | [`Triggers`](../../doc/models/triggers.md) | Required | - | Triggers getTriggers() | setTriggers(Triggers triggers) |
| `BadgeIds` | `List<Object>` | Required | - | List<Object> getBadgeIds() | setBadgeIds(List<Object> badgeIds) |
| `BadgeGroupingIds` | `List<Object>` | Required | - | List<Object> getBadgeGroupingIds() | setBadgeGroupingIds(List<Object> badgeGroupingIds) |
| `BadgeTypeIds` | `List<Object>` | Required | - | List<Object> getBadgeTypeIds() | setBadgeTypeIds(List<Object> badgeTypeIds) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.AdminBadges;
import com.example.discourse.models.Triggers;
import java.io.IOException;
import java.util.Arrays;

AdminBadges adminBadges = new AdminBadges.Builder(
    Arrays.asList(
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
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.build();
```

