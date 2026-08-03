
# Group 10

## Structure

`Group10`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Automatic` | `boolean` | Required | - | boolean getAutomatic() | setAutomatic(boolean automatic) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `DisplayName` | `String` | Required | - | String getDisplayName() | setDisplayName(String displayName) |
| `UserCount` | `int` | Required | - | int getUserCount() | setUserCount(int userCount) |
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
| `FlairGroupId` | `Integer` | Optional | - | Integer getFlairGroupId() | setFlairGroupId(Integer flairGroupId) |
| `BioRaw` | `String` | Required | - | String getBioRaw() | setBioRaw(String bioRaw) |
| `BioCooked` | `String` | Required | - | String getBioCooked() | setBioCooked(String bioCooked) |
| `BioExcerpt` | `String` | Required | - | String getBioExcerpt() | setBioExcerpt(String bioExcerpt) |
| `PublicAdmission` | `boolean` | Required | - | boolean getPublicAdmission() | setPublicAdmission(boolean publicAdmission) |
| `PublicExit` | `boolean` | Required | - | boolean getPublicExit() | setPublicExit(boolean publicExit) |
| `AllowMembershipRequests` | `boolean` | Required | - | boolean getAllowMembershipRequests() | setAllowMembershipRequests(boolean allowMembershipRequests) |
| `FullName` | `String` | Required | - | String getFullName() | setFullName(String fullName) |
| `DefaultNotificationLevel` | `int` | Required | - | int getDefaultNotificationLevel() | setDefaultNotificationLevel(int defaultNotificationLevel) |
| `MembershipRequestTemplate` | `String` | Required | - | String getMembershipRequestTemplate() | setMembershipRequestTemplate(String membershipRequestTemplate) |
| `MembersVisibilityLevel` | `int` | Required | - | int getMembersVisibilityLevel() | setMembersVisibilityLevel(int membersVisibilityLevel) |
| `CanSeeMembers` | `boolean` | Required | - | boolean getCanSeeMembers() | setCanSeeMembers(boolean canSeeMembers) |
| `CanAdminGroup` | `boolean` | Required | - | boolean getCanAdminGroup() | setCanAdminGroup(boolean canAdminGroup) |
| `PublishReadState` | `boolean` | Required | - | boolean getPublishReadState() | setPublishReadState(boolean publishReadState) |

## Example

```java
import com.example.discourse.models.Group10;

Group10 group10 = new Group10.Builder(
    28,
    false,
    "name2",
    "display_name2",
    132,
    112,
    224,
    184,
    false,
    "title2",
    "grant_trust_level4",
    "incoming_email8",
    false,
    "flair_url2",
    "flair_bg_color6",
    "flair_color6",
    "bio_raw6",
    "bio_cooked2",
    "bio_excerpt6",
    false,
    false,
    false,
    "full_name8",
    244,
    "membership_request_template2",
    132,
    false,
    false,
    false
)
.flairGroupId(78)
.build();
```

