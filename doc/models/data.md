
# Data

*This model accepts additional fields of type Object.*

## Structure

`Data`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `BadgeId` | `Integer` | Optional | - | Integer getBadgeId() | setBadgeId(Integer badgeId) |
| `BadgeName` | `String` | Optional | - | String getBadgeName() | setBadgeName(String badgeName) |
| `BadgeSlug` | `String` | Optional | - | String getBadgeSlug() | setBadgeSlug(String badgeSlug) |
| `BadgeTitle` | `Boolean` | Optional | - | Boolean getBadgeTitle() | setBadgeTitle(Boolean badgeTitle) |
| `Username` | `String` | Optional | - | String getUsername() | setUsername(String username) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Data;
import java.io.IOException;

Data data = new Data.Builder()
    .badgeId(98)
    .badgeName("badge_name8")
    .badgeSlug("badge_slug4")
    .badgeTitle(false)
    .username("username0")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

