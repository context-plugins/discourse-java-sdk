
# Badge 1

## Structure

`Badge1`

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
| `ImageUploadId` | `Integer` | Required | - | Integer getImageUploadId() | setImageUploadId(Integer imageUploadId) |
| `Listable` | `boolean` | Required | - | boolean getListable() | setListable(boolean listable) |
| `Enabled` | `boolean` | Required | - | boolean getEnabled() | setEnabled(boolean enabled) |
| `BadgeGroupingId` | `int` | Required | - | int getBadgeGroupingId() | setBadgeGroupingId(int badgeGroupingId) |
| `System` | `boolean` | Required | - | boolean getSystem() | setSystem(boolean system) |
| `LongDescription` | `String` | Required | - | String getLongDescription() | setLongDescription(String longDescription) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `ManuallyGrantable` | `boolean` | Required | - | boolean getManuallyGrantable() | setManuallyGrantable(boolean manuallyGrantable) |
| `Query` | `String` | Required | - | String getQuery() | setQuery(String query) |
| `Trigger` | `String` | Required | - | String getTrigger() | setTrigger(String trigger) |
| `TargetPosts` | `boolean` | Required | - | boolean getTargetPosts() | setTargetPosts(boolean targetPosts) |
| `AutoRevoke` | `boolean` | Required | - | boolean getAutoRevoke() | setAutoRevoke(boolean autoRevoke) |
| `ShowPosts` | `boolean` | Required | - | boolean getShowPosts() | setShowPosts(boolean showPosts) |
| `BadgeTypeId` | `int` | Required | - | int getBadgeTypeId() | setBadgeTypeId(int badgeTypeId) |
| `ShowInPostHeader` | `boolean` | Required | - | boolean getShowInPostHeader() | setShowInPostHeader(boolean showInPostHeader) |

## Example

```java
import com.example.discourse.models.Badge1;

Badge1 badge1 = new Badge1.Builder(
    184,
    "name8",
    "description8",
    198,
    false,
    false,
    "icon0",
    "image_url4",
    200,
    false,
    false,
    64,
    false,
    "long_description0",
    "slug2",
    false,
    "query8",
    "trigger0",
    false,
    false,
    false,
    208,
    false
)
.build();
```

