
# Topic List 1

*This model accepts additional fields of type Object.*

## Structure

`TopicList1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CanCreateTopic` | `Boolean` | Optional | - | Boolean getCanCreateTopic() | setCanCreateTopic(Boolean canCreateTopic) |
| `Draft` | `String` | Optional | - | String getDraft() | setDraft(String draft) |
| `DraftKey` | `String` | Optional | - | String getDraftKey() | setDraftKey(String draftKey) |
| `DraftSequence` | `Integer` | Optional | - | Integer getDraftSequence() | setDraftSequence(Integer draftSequence) |
| `PerPage` | `Integer` | Optional | - | Integer getPerPage() | setPerPage(Integer perPage) |
| `Topics` | [`List<Topic2>`](../../doc/models/topic-2.md) | Optional | - | List<Topic2> getTopics() | setTopics(List<Topic2> topics) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TopicList1;
import java.io.IOException;

TopicList1 topicList1 = new TopicList1.Builder()
    .canCreateTopic(false)
    .draft("draft0")
    .draftKey("draft_key8")
    .draftSequence(152)
    .perPage(44)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

