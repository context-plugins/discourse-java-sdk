
# Invites Create Multiple Json Request

*This model accepts additional fields of type Object.*

## Structure

`InvitesCreateMultipleJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Email` | `String` | Optional | pass 1 email per invite to be generated. other properties<br>will be shared by each invite. | String getEmail() | setEmail(String email) |
| `SkipEmail` | `Boolean` | Optional | **Default**: `false` | Boolean getSkipEmail() | setSkipEmail(Boolean skipEmail) |
| `CustomMessage` | `String` | Optional | optional, for email invites | String getCustomMessage() | setCustomMessage(String customMessage) |
| `MaxRedemptionsAllowed` | `Integer` | Optional | optional, for link invites<br><br>**Default**: `1` | Integer getMaxRedemptionsAllowed() | setMaxRedemptionsAllowed(Integer maxRedemptionsAllowed) |
| `TopicId` | `Integer` | Optional | - | Integer getTopicId() | setTopicId(Integer topicId) |
| `GroupIds` | `String` | Optional | Optional, either this or `group_names`. Comma separated<br>list for multiple ids. | String getGroupIds() | setGroupIds(String groupIds) |
| `GroupNames` | `String` | Optional | Optional, either this or `group_ids`. Comma separated<br>list for multiple names. | String getGroupNames() | setGroupNames(String groupNames) |
| `ExpiresAt` | `String` | Optional | optional, if not supplied, the invite_expiry_days site<br>setting is used | String getExpiresAt() | setExpiresAt(String expiresAt) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.InvitesCreateMultipleJsonRequest;
import java.io.IOException;

InvitesCreateMultipleJsonRequest invitesCreateMultipleJsonRequest = new InvitesCreateMultipleJsonRequest.Builder()
    .email("[\n  \"not-a-user-yet-1@example.com\",\n  \"not-a-user-yet-2@example.com\"\n]")
    .skipEmail(false)
    .customMessage("custom_message6")
    .maxRedemptionsAllowed(5)
    .topicId(92)
    .groupIds("42,43")
    .groupNames("foo,bar")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

