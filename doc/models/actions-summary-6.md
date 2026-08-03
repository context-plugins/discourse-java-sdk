
# Actions Summary 6

*This model accepts additional fields of type Object.*

## Structure

`ActionsSummary6`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `CanAct` | `Boolean` | Optional | - | Boolean getCanAct() | setCanAct(Boolean canAct) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary6;
import java.io.IOException;

ActionsSummary6 actionsSummary6 = new ActionsSummary6.Builder()
    .id(120)
    .canAct(false)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

