
# Topic List 2

*This model accepts additional fields of type Object.*

## Structure

`TopicList2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CanCreateTopic` | `Boolean` | Optional | - | Boolean getCanCreateTopic() | setCanCreateTopic(Boolean canCreateTopic) |
| `Draft` | `String` | Optional | - | String getDraft() | setDraft(String draft) |
| `DraftKey` | `String` | Optional | - | String getDraftKey() | setDraftKey(String draftKey) |
| `DraftSequence` | `Integer` | Optional | - | Integer getDraftSequence() | setDraftSequence(Integer draftSequence) |
| `PerPage` | `Integer` | Optional | - | Integer getPerPage() | setPerPage(Integer perPage) |
| `Topics` | [`List<Topic3>`](../../doc/models/topic-3.md) | Optional | - | List<Topic3> getTopics() | setTopics(List<Topic3> topics) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TopicList2;
import java.io.IOException;

TopicList2 topicList2 = new TopicList2.Builder()
    .canCreateTopic(false)
    .draft("draft6")
    .draftKey("draft_key4")
    .draftSequence(218)
    .perPage(234)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

