
# Topic List 3

*This model accepts additional fields of type Object.*

## Structure

`TopicList3`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CanCreateTopic` | `Boolean` | Optional | - | Boolean getCanCreateTopic() | setCanCreateTopic(Boolean canCreateTopic) |
| `Draft` | `String` | Optional | - | String getDraft() | setDraft(String draft) |
| `DraftKey` | `String` | Optional | - | String getDraftKey() | setDraftKey(String draftKey) |
| `DraftSequence` | `Integer` | Optional | - | Integer getDraftSequence() | setDraftSequence(Integer draftSequence) |
| `PerPage` | `Integer` | Optional | - | Integer getPerPage() | setPerPage(Integer perPage) |
| `Tags` | [`List<Tag4>`](../../doc/models/tag-4.md) | Optional | - | List<Tag4> getTags() | setTags(List<Tag4> tags) |
| `Topics` | [`List<Topic4>`](../../doc/models/topic-4.md) | Optional | - | List<Topic4> getTopics() | setTopics(List<Topic4> topics) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TopicList3;
import java.io.IOException;

TopicList3 topicList3 = new TopicList3.Builder()
    .canCreateTopic(false)
    .draft("draft2")
    .draftKey("draft_key0")
    .draftSequence(138)
    .perPage(58)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

