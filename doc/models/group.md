
# Group

## Structure

`Group`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `FullName` | `String` | Optional | - | String getFullName() | setFullName(String fullName) |
| `BioRaw` | `String` | Optional | About Group | String getBioRaw() | setBioRaw(String bioRaw) |
| `Usernames` | `String` | Optional | comma,separated | String getUsernames() | setUsernames(String usernames) |
| `OwnerUsernames` | `String` | Optional | comma,separated | String getOwnerUsernames() | setOwnerUsernames(String ownerUsernames) |
| `AutomaticMembershipEmailDomains` | `String` | Optional | pipe\|separated | String getAutomaticMembershipEmailDomains() | setAutomaticMembershipEmailDomains(String automaticMembershipEmailDomains) |
| `VisibilityLevel` | `Integer` | Optional | - | Integer getVisibilityLevel() | setVisibilityLevel(Integer visibilityLevel) |
| `PrimaryGroup` | `Boolean` | Optional | - | Boolean getPrimaryGroup() | setPrimaryGroup(Boolean primaryGroup) |
| `FlairIcon` | `String` | Optional | - | String getFlairIcon() | setFlairIcon(String flairIcon) |
| `FlairUploadId` | `Integer` | Optional | - | Integer getFlairUploadId() | setFlairUploadId(Integer flairUploadId) |
| `FlairBgColor` | `String` | Optional | - | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `PublicAdmission` | `Boolean` | Optional | - | Boolean getPublicAdmission() | setPublicAdmission(Boolean publicAdmission) |
| `PublicExit` | `Boolean` | Optional | - | Boolean getPublicExit() | setPublicExit(Boolean publicExit) |
| `DefaultNotificationLevel` | `Integer` | Optional | - | Integer getDefaultNotificationLevel() | setDefaultNotificationLevel(Integer defaultNotificationLevel) |
| `MutedCategoryIds` | `List<Integer>` | Optional | - | List<Integer> getMutedCategoryIds() | setMutedCategoryIds(List<Integer> mutedCategoryIds) |
| `RegularCategoryIds` | `List<Integer>` | Optional | - | List<Integer> getRegularCategoryIds() | setRegularCategoryIds(List<Integer> regularCategoryIds) |
| `WatchingCategoryIds` | `List<Integer>` | Optional | - | List<Integer> getWatchingCategoryIds() | setWatchingCategoryIds(List<Integer> watchingCategoryIds) |
| `TrackingCategoryIds` | `List<Integer>` | Optional | - | List<Integer> getTrackingCategoryIds() | setTrackingCategoryIds(List<Integer> trackingCategoryIds) |
| `WatchingFirstPostCategoryIds` | `List<Integer>` | Optional | - | List<Integer> getWatchingFirstPostCategoryIds() | setWatchingFirstPostCategoryIds(List<Integer> watchingFirstPostCategoryIds) |

## Example

```java
import com.example.discourse.models.Group;

Group group = new Group.Builder(
    "name8"
)
.fullName("full_name4")
.bioRaw("bio_raw0")
.usernames("usernames0")
.ownerUsernames("owner_usernames8")
.automaticMembershipEmailDomains("automatic_membership_email_domains2")
.build();
```

