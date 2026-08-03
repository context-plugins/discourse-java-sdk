
# T Status Json Response

*This model accepts additional fields of type Object.*

## Structure

`TStatusJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Optional | - | String getSuccess() | setSuccess(String success) |
| `TopicStatusUpdate` | `String` | Optional | - | String getTopicStatusUpdate() | setTopicStatusUpdate(String topicStatusUpdate) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TStatusJsonResponse;
import java.io.IOException;

TStatusJsonResponse tStatusJsonResponse = new TStatusJsonResponse.Builder()
    .success("OK")
    .topicStatusUpdate("topic_status_update8")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

