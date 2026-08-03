
# T Change Timestamp Json Request

*This model accepts additional fields of type Object.*

## Structure

`TChangeTimestampJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Timestamp` | `String` | Required | - | String getTimestamp() | setTimestamp(String timestamp) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TChangeTimestampJsonRequest;
import java.io.IOException;

TChangeTimestampJsonRequest tChangeTimestampJsonRequest = new TChangeTimestampJsonRequest.Builder(
    "1594291380"
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

