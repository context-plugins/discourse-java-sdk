
# Badge

## Structure

`Badge`

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
| `LongDescription` | `String` | Required | - | String getLongDescription() | setLongDescription(String longDescription) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `ManuallyGrantable` | `boolean` | Required | - | boolean getManuallyGrantable() | setManuallyGrantable(boolean manuallyGrantable) |
| `Query` | `String` | Required | - | String getQuery() | setQuery(String query) |
| `Trigger` | `Integer` | Required | - | Integer getTrigger() | setTrigger(Integer trigger) |
| `TargetPosts` | `boolean` | Required | - | boolean getTargetPosts() | setTargetPosts(boolean targetPosts) |
| `AutoRevoke` | `boolean` | Required | - | boolean getAutoRevoke() | setAutoRevoke(boolean autoRevoke) |
| `ShowPosts` | `boolean` | Required | - | boolean getShowPosts() | setShowPosts(boolean showPosts) |
| `I18NName` | `String` | Optional | - | String getI18NName() | setI18NName(String i18NName) |
| `ImageUploadId` | `Integer` | Required | - | Integer getImageUploadId() | setImageUploadId(Integer imageUploadId) |
| `BadgeTypeId` | `int` | Required | - | int getBadgeTypeId() | setBadgeTypeId(int badgeTypeId) |
| `ShowInPostHeader` | `boolean` | Required | - | boolean getShowInPostHeader() | setShowInPostHeader(boolean showInPostHeader) |

## Example

```java
import com.example.discourse.models.Badge;

Badge badge = new Badge.Builder(
    184,
    "name0",
    "description0",
    198,
    false,
    false,
    "icon2",
    "image_url6",
    false,
    false,
    192,
    false,
    "long_description2",
    "slug6",
    false,
    "query0",
    42,
    false,
    false,
    false,
    56,
    208,
    false
)
.i18NName("i18n_name4")
.build();
```

