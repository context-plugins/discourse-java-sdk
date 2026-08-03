
# Group 1

## Structure

`Group1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Automatic` | `boolean` | Required | - | boolean getAutomatic() | setAutomatic(boolean automatic) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
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
| `IsGroupUser` | `boolean` | Required | - | boolean getIsGroupUser() | setIsGroupUser(boolean isGroupUser) |
| `MembersVisibilityLevel` | `int` | Required | - | int getMembersVisibilityLevel() | setMembersVisibilityLevel(int membersVisibilityLevel) |
| `CanSeeMembers` | `boolean` | Required | - | boolean getCanSeeMembers() | setCanSeeMembers(boolean canSeeMembers) |
| `CanAdminGroup` | `boolean` | Required | - | boolean getCanAdminGroup() | setCanAdminGroup(boolean canAdminGroup) |
| `CanEditGroup` | `Boolean` | Optional | - | Boolean getCanEditGroup() | setCanEditGroup(Boolean canEditGroup) |
| `PublishReadState` | `boolean` | Required | - | boolean getPublishReadState() | setPublishReadState(boolean publishReadState) |
| `IsGroupOwnerDisplay` | `boolean` | Required | - | boolean getIsGroupOwnerDisplay() | setIsGroupOwnerDisplay(boolean isGroupOwnerDisplay) |
| `Mentionable` | `boolean` | Required | - | boolean getMentionable() | setMentionable(boolean mentionable) |
| `Messageable` | `boolean` | Required | - | boolean getMessageable() | setMessageable(boolean messageable) |
| `AutomaticMembershipEmailDomains` | `String` | Required | - | String getAutomaticMembershipEmailDomains() | setAutomaticMembershipEmailDomains(String automaticMembershipEmailDomains) |
| `SmtpUpdatedAt` | `String` | Optional | - | String getSmtpUpdatedAt() | setSmtpUpdatedAt(String smtpUpdatedAt) |
| `SmtpUpdatedBy` | `Object` | Optional | - | Object getSmtpUpdatedBy() | setSmtpUpdatedBy(Object smtpUpdatedBy) |
| `SmtpEnabled` | `Boolean` | Optional | - | Boolean getSmtpEnabled() | setSmtpEnabled(Boolean smtpEnabled) |
| `SmtpServer` | `String` | Required | - | String getSmtpServer() | setSmtpServer(String smtpServer) |
| `SmtpPort` | `String` | Required | - | String getSmtpPort() | setSmtpPort(String smtpPort) |
| `SmtpSslMode` | `Integer` | Required | - | Integer getSmtpSslMode() | setSmtpSslMode(Integer smtpSslMode) |
| `EmailUsername` | `String` | Required | - | String getEmailUsername() | setEmailUsername(String emailUsername) |
| `EmailFromAlias` | `String` | Optional | - | String getEmailFromAlias() | setEmailFromAlias(String emailFromAlias) |
| `EmailPassword` | `String` | Required | - | String getEmailPassword() | setEmailPassword(String emailPassword) |
| `MessageCount` | `int` | Required | - | int getMessageCount() | setMessageCount(int messageCount) |
| `AllowUnknownSenderTopicReplies` | `boolean` | Required | - | boolean getAllowUnknownSenderTopicReplies() | setAllowUnknownSenderTopicReplies(boolean allowUnknownSenderTopicReplies) |
| `AssociatedGroupIds` | `List<Object>` | Optional | - | List<Object> getAssociatedGroupIds() | setAssociatedGroupIds(List<Object> associatedGroupIds) |
| `WatchingCategoryIds` | `List<Object>` | Required | - | List<Object> getWatchingCategoryIds() | setWatchingCategoryIds(List<Object> watchingCategoryIds) |
| `TrackingCategoryIds` | `List<Object>` | Required | - | List<Object> getTrackingCategoryIds() | setTrackingCategoryIds(List<Object> trackingCategoryIds) |
| `WatchingFirstPostCategoryIds` | `List<Object>` | Required | - | List<Object> getWatchingFirstPostCategoryIds() | setWatchingFirstPostCategoryIds(List<Object> watchingFirstPostCategoryIds) |
| `RegularCategoryIds` | `List<Object>` | Required | - | List<Object> getRegularCategoryIds() | setRegularCategoryIds(List<Object> regularCategoryIds) |
| `MutedCategoryIds` | `List<Object>` | Required | - | List<Object> getMutedCategoryIds() | setMutedCategoryIds(List<Object> mutedCategoryIds) |
| `WatchingTags` | `List<Object>` | Optional | - | List<Object> getWatchingTags() | setWatchingTags(List<Object> watchingTags) |
| `WatchingFirstPostTags` | `List<Object>` | Optional | - | List<Object> getWatchingFirstPostTags() | setWatchingFirstPostTags(List<Object> watchingFirstPostTags) |
| `TrackingTags` | `List<Object>` | Optional | - | List<Object> getTrackingTags() | setTrackingTags(List<Object> trackingTags) |
| `RegularTags` | `List<Object>` | Optional | - | List<Object> getRegularTags() | setRegularTags(List<Object> regularTags) |
| `MutedTags` | `List<Object>` | Optional | - | List<Object> getMutedTags() | setMutedTags(List<Object> mutedTags) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Group1;
import java.io.IOException;
import java.util.Arrays;

Group1 group1 = new Group1.Builder(
    18,
    false,
    "name2",
    102,
    214,
    194,
    false,
    "title8",
    "grant_trust_level4",
    "incoming_email2",
    false,
    "flair_url2",
    "flair_bg_color6",
    "flair_color6",
    "bio_raw6",
    "bio_cooked8",
    "bio_excerpt6",
    false,
    false,
    false,
    "full_name8",
    234,
    "membership_request_template8",
    false,
    122,
    false,
    false,
    false,
    false,
    false,
    false,
    "automatic_membership_email_domains6",
    "smtp_server4",
    "smtp_port4",
    30,
    "email_username0",
    "email_password4",
    224,
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
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
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.userCount(142)
.canEditGroup(false)
.smtpUpdatedAt("smtp_updated_at0")
.smtpUpdatedBy(ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.smtpEnabled(false)
.build();
```

