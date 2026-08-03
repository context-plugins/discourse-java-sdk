
# Extra

*This model accepts additional fields of type Object.*

## Structure

`Extra`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Categories` | `String` | Optional | - | String getCategories() | setCategories(String categories) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extra;
import java.io.IOException;

Extra extra = new Extra.Builder()
    .categories("categories8")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

