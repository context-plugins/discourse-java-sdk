
# Posts Json Request

## Structure

`PostsJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Title` | `String` | Optional | Required if creating a new topic or new private message. | String getTitle() | setTitle(String title) |
| `Raw` | `String` | Required | - | String getRaw() | setRaw(String raw) |
| `TopicId` | `Integer` | Optional | Required if creating a new post. | Integer getTopicId() | setTopicId(Integer topicId) |
| `Category` | `Integer` | Optional | Optional if creating a new topic, and ignored if creating<br>a new post. | Integer getCategory() | setCategory(Integer category) |
| `TargetRecipients` | `String` | Optional | Required for private message, comma separated. | String getTargetRecipients() | setTargetRecipients(String targetRecipients) |
| `TargetUsernames` | `String` | Optional | Deprecated. Use target_recipients instead. | String getTargetUsernames() | setTargetUsernames(String targetUsernames) |
| `Archetype` | `String` | Optional | Required for new private message. | String getArchetype() | setArchetype(String archetype) |
| `CreatedAt` | `String` | Optional | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `ReplyToPostNumber` | `Integer` | Optional | Optional, the post number to reply to inside a topic. | Integer getReplyToPostNumber() | setReplyToPostNumber(Integer replyToPostNumber) |
| `EmbedUrl` | `String` | Optional | Provide a URL from a remote system to associate a forum<br>topic with that URL, typically for using Discourse as a comments<br>system for an external blog. | String getEmbedUrl() | setEmbedUrl(String embedUrl) |
| `ExternalId` | `String` | Optional | Provide an external_id from a remote system to associate<br>a forum topic with that id. | String getExternalId() | setExternalId(String externalId) |
| `AutoTrack` | `Boolean` | Optional | If false, the user will not track the topic. By default,<br>the user will track the topic. | Boolean getAutoTrack() | setAutoTrack(Boolean autoTrack) |

## Example

```java
import com.example.discourse.models.PostsJsonRequest;

PostsJsonRequest postsJsonRequest = new PostsJsonRequest.Builder(
    "raw2"
)
.title("title0")
.topicId(230)
.category(112)
.targetRecipients("blake,sam")
.targetUsernames("target_usernames8")
.archetype("private_message")
.build();
```

