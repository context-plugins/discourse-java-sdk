
# Group 7

## Structure

`Group7`

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
import com.example.discourse.models.Group7;

Group7 group7 = new Group7.Builder(
    60,
    false,
    "name8",
    "display_name8",
    100,
    144,
    0,
    152,
    false,
    "title6",
    "grant_trust_level0",
    "incoming_email2",
    false,
    "flair_url8",
    "flair_bg_color2",
    "flair_color2",
    "bio_raw0",
    "bio_cooked6",
    "bio_excerpt2",
    false,
    false,
    false,
    "full_name4",
    20,
    "membership_request_template6",
    164,
    false,
    false,
    false
)
.build();
```

