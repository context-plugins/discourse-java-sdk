
# Topic List 5

*This model accepts additional fields of type Object.*

## Structure

`TopicList5`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CanCreateTopic` | `Boolean` | Optional | - | Boolean getCanCreateTopic() | setCanCreateTopic(Boolean canCreateTopic) |
| `Draft` | `String` | Optional | - | String getDraft() | setDraft(String draft) |
| `DraftKey` | `String` | Optional | - | String getDraftKey() | setDraftKey(String draftKey) |
| `DraftSequence` | `Integer` | Optional | - | Integer getDraftSequence() | setDraftSequence(Integer draftSequence) |
| `ForPeriod` | `String` | Optional | - | String getForPeriod() | setForPeriod(String forPeriod) |
| `PerPage` | `Integer` | Optional | - | Integer getPerPage() | setPerPage(Integer perPage) |
| `Topics` | [`List<Topic7>`](../../doc/models/topic-7.md) | Optional | - | List<Topic7> getTopics() | setTopics(List<Topic7> topics) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TopicList5;
import java.io.IOException;

TopicList5 topicList5 = new TopicList5.Builder()
    .canCreateTopic(false)
    .draft("draft0")
    .draftKey("draft_key8")
    .draftSequence(138)
    .forPeriod("for_period0")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

