
# T Json Request

*This model accepts additional fields of type Object.*

## Structure

`TJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Topic` | [`Topic5`](../../doc/models/topic-5.md) | Optional | - | Topic5 getTopic() | setTopic(Topic5 topic) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TJsonRequest;
import com.example.discourse.models.Topic5;
import java.io.IOException;

TJsonRequest tJsonRequest = new TJsonRequest.Builder()
    .topic(new Topic5.Builder()
        .title("title4")
        .categoryId(208)
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

