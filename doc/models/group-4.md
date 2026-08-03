
# Group 4

## Structure

`Group4`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Automatic` | `boolean` | Required | - | boolean getAutomatic() | setAutomatic(boolean automatic) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `DisplayName` | `String` | Required | - | String getDisplayName() | setDisplayName(String displayName) |
| `UserCount` | `Integer` | Optional | - | Integer getUserCount() | setUserCount(Integer userCount) |
| `MentionableLevel` | `int` | Required | - | int getMentionableLevel() | setMentionableLevel(int mentionableLevel) |
| `MessageableLevel` | `int` | Required | - | int getMessageableLevel() | setMessageableLevel(int messageableLevel) |
| `VisibilityLevel` | `int` | Required | - | int getVisibilityLevel() | setVisibilityLevel(int visibilityLevel) |
| `PrimaryGroup` | `boolean` | Required | - | boolean getPrimaryGroup() | setPrimaryGroup(boolean primaryGroup) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `GrantTrustLevel` | `String` | Required | - | String getGrantTrustLevel() | setGrantTrustLevel(String grantTrustLevel) |
| `IncomingEmail` | `String` | Required | - | String getIncomingEmail() | setIncomingEmail(String incomingEmail) |
| `HasMessages` | `boolean` | Required | - | boolean getHasMessages() | setHasMessages(boolean hasMessages) |
| `FlairUrl` | `String` | Required | - | String getFlairUrl() | setFlairUrl(String flairUrl) |
| `FlairBgColor` | `String` | Required | - | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `FlairColor` | `String` | Required | - | String getFlairColor() | setFlairColor(String flairColor) |
| `BioRaw` | `String` | Required | - | String getBioRaw() | setBioRaw(String bioRaw) |
| `BioCooked` | `String` | Required | - | String getBioCooked() | setBioCooked(String bioCooked) |
| `BioExcerpt` | `String` | Required | - | String getBioExcerpt() | setBioExcerpt(String bioExcerpt) |
| `PublicAdmission` | `boolean` | Required | - | boolean getPublicAdmission() | setPublicAdmission(boolean publicAdmission) |
| `PublicExit` | `boolean` | Required | - | boolean getPublicExit() | setPublicExit(boolean publicExit) |
| `AllowMembershipRequests` | `boolean` | Required | - | boolean getAllowMembershipRequests() | setAllowMembershipRequests(boolean allowMembershipRequests) |
| `FullName` | `String` | Required | - | String getFullName() | setFullName(String fullName) |
| `DefaultNotificationLevel` | `int` | Required | - | int getDefaultNotificationLevel() | setDefaultNotificationLevel(int defaultNotificationLevel) |
| `MembershipRequestTemplate` | `String` | Required | - | String getMembershipRequestTemplate() | setMembershipRequestTemplate(String membershipRequestTemplate) |
| `IsGroupUser` | `Boolean` | Optional | - | Boolean getIsGroupUser() | setIsGroupUser(Boolean isGroupUser) |
| `IsGroupOwner` | `Boolean` | Optional | - | Boolean getIsGroupOwner() | setIsGroupOwner(Boolean isGroupOwner) |
| `MembersVisibilityLevel` | `int` | Required | - | int getMembersVisibilityLevel() | setMembersVisibilityLevel(int membersVisibilityLevel) |
| `CanSeeMembers` | `boolean` | Required | - | boolean getCanSeeMembers() | setCanSeeMembers(boolean canSeeMembers) |
| `CanAdminGroup` | `boolean` | Required | - | boolean getCanAdminGroup() | setCanAdminGroup(boolean canAdminGroup) |
| `CanEditGroup` | `Boolean` | Optional | - | Boolean getCanEditGroup() | setCanEditGroup(Boolean canEditGroup) |
| `PublishReadState` | `boolean` | Required | - | boolean getPublishReadState() | setPublishReadState(boolean publishReadState) |

## Example

```java
import com.example.discourse.models.Group4;

Group4 group4 = new Group4.Builder(
    252,
    false,
    "name0",
    "display_name0",
    80,
    192,
    216,
    false,
    "title4",
    "grant_trust_level2",
    "incoming_email0",
    false,
    "flair_url0",
    "flair_bg_color4",
    "flair_color6",
    "bio_raw8",
    "bio_cooked4",
    "bio_excerpt4",
    false,
    false,
    false,
    "full_name6",
    44,
    "membership_request_template4",
    100,
    false,
    false,
    false
)
.userCount(164)
.isGroupUser(false)
.isGroupOwner(false)
.canEditGroup(false)
.build();
```

