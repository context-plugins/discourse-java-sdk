
# Invites Json Request

## Structure

`InvitesJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Email` | `String` | Optional | required for email invites only | String getEmail() | setEmail(String email) |
| `SkipEmail` | `Boolean` | Optional | **Default**: `false` | Boolean getSkipEmail() | setSkipEmail(Boolean skipEmail) |
| `CustomMessage` | `String` | Optional | optional, for email invites | String getCustomMessage() | setCustomMessage(String customMessage) |
| `MaxRedemptionsAllowed` | `Integer` | Optional | optional, for link invites<br><br>**Default**: `1` | Integer getMaxRedemptionsAllowed() | setMaxRedemptionsAllowed(Integer maxRedemptionsAllowed) |
| `TopicId` | `Integer` | Optional | - | Integer getTopicId() | setTopicId(Integer topicId) |
| `GroupIds` | `String` | Optional | Optional, either this or `group_names`. Comma separated<br>list for multiple ids. | String getGroupIds() | setGroupIds(String groupIds) |
| `GroupNames` | `String` | Optional | Optional, either this or `group_ids`. Comma separated<br>list for multiple names. | String getGroupNames() | setGroupNames(String groupNames) |
| `ExpiresAt` | `String` | Optional | optional, if not supplied, the invite_expiry_days site<br>setting is used | String getExpiresAt() | setExpiresAt(String expiresAt) |

## Example

```java
import com.example.discourse.models.InvitesJsonRequest;

InvitesJsonRequest invitesJsonRequest = new InvitesJsonRequest.Builder()
    .email("not-a-user-yet@example.com")
    .skipEmail(false)
    .customMessage("custom_message2")
    .maxRedemptionsAllowed(5)
    .topicId(154)
    .groupIds("42,43")
    .groupNames("foo,bar")
    .build();
```

