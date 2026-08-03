
# Badge 3

## Structure

`Badge3`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `GrantCount` | `int` | Required | - | int getGrantCount() | setGrantCount(int grantCount) |
| `AllowTitle` | `boolean` | Required | - | boolean getAllowTitle() | setAllowTitle(boolean allowTitle) |
| `MultipleGrant` | `boolean` | Required | - | boolean getMultipleGrant() | setMultipleGrant(boolean multipleGrant) |
| `Icon` | `String` | Required | - | String getIcon() | setIcon(String icon) |
| `ImageUrl` | `String` | Required | - | String getImageUrl() | setImageUrl(String imageUrl) |
| `Listable` | `boolean` | Required | - | boolean getListable() | setListable(boolean listable) |
| `Enabled` | `boolean` | Required | - | boolean getEnabled() | setEnabled(boolean enabled) |
| `BadgeGroupingId` | `int` | Required | - | int getBadgeGroupingId() | setBadgeGroupingId(int badgeGroupingId) |
| `System` | `boolean` | Required | - | boolean getSystem() | setSystem(boolean system) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `ManuallyGrantable` | `boolean` | Required | - | boolean getManuallyGrantable() | setManuallyGrantable(boolean manuallyGrantable) |
| `BadgeTypeId` | `int` | Required | - | int getBadgeTypeId() | setBadgeTypeId(int badgeTypeId) |

## Example

```java
import com.example.discourse.models.Badge3;

Badge3 badge3 = new Badge3.Builder(
    26,
    "name0",
    "description0",
    40,
    false,
    false,
    "icon2",
    "image_url6",
    false,
    false,
    94,
    false,
    "slug6",
    false,
    50
)
.build();
```

