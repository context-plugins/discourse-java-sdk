
# Topic 5

*This model accepts additional fields of type Object.*

## Structure

`Topic5`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Title` | `String` | Optional | - | String getTitle() | setTitle(String title) |
| `CategoryId` | `Integer` | Optional | - | Integer getCategoryId() | setCategoryId(Integer categoryId) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Topic5;
import java.io.IOException;

Topic5 topic5 = new Topic5.Builder()
    .title("title0")
    .categoryId(98)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

