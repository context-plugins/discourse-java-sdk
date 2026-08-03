
# Extras 3

*This model accepts additional fields of type Object.*

## Structure

`Extras3`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Categories` | `List<Object>` | Optional | - | List<Object> getCategories() | setCategories(List<Object> categories) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extras3;
import java.io.IOException;
import java.util.Arrays;

Extras3 extras3 = new Extras3.Builder()
    .categories(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

