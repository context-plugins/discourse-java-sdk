
# T Json Response 1

*This model accepts additional fields of type Object.*

## Structure

`TJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `BasicTopic` | [`BasicTopic`](../../doc/models/basic-topic.md) | Optional | - | BasicTopic getBasicTopic() | setBasicTopic(BasicTopic basicTopic) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.BasicTopic;
import com.example.discourse.models.TJsonResponse1;
import java.io.IOException;

TJsonResponse1 tJsonResponse1 = new TJsonResponse1.Builder()
    .basicTopic(new BasicTopic.Builder()
        .id(150)
        .title("title0")
        .fancyTitle("fancy_title4")
        .slug("slug2")
        .postsCount(32)
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

