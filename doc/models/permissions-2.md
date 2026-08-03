
# Permissions 2

*This model accepts additional fields of type Object.*

## Structure

`Permissions2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Everyone` | `Integer` | Optional | - | Integer getEveryone() | setEveryone(Integer everyone) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Permissions2;
import java.io.IOException;

Permissions2 permissions2 = new Permissions2.Builder()
    .everyone(242)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

