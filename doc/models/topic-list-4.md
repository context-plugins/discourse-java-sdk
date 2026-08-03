
# Topic List 4

*This model accepts additional fields of type Object.*

## Structure

`TopicList4`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CanCreateTopic` | `Boolean` | Optional | - | Boolean getCanCreateTopic() | setCanCreateTopic(Boolean canCreateTopic) |
| `Draft` | `String` | Optional | - | String getDraft() | setDraft(String draft) |
| `DraftKey` | `String` | Optional | - | String getDraftKey() | setDraftKey(String draftKey) |
| `DraftSequence` | `Integer` | Optional | - | Integer getDraftSequence() | setDraftSequence(Integer draftSequence) |
| `PerPage` | `Integer` | Optional | - | Integer getPerPage() | setPerPage(Integer perPage) |
| `Topics` | [`List<Topic6>`](../../doc/models/topic-6.md) | Optional | - | List<Topic6> getTopics() | setTopics(List<Topic6> topics) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TopicList4;
import java.io.IOException;

TopicList4 topicList4 = new TopicList4.Builder()
    .canCreateTopic(false)
    .draft("draft4")
    .draftKey("draft_key2")
    .draftSequence(220)
    .perPage(232)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

