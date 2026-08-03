
# Tag Groups Json Request 1

*This model accepts additional fields of type Object.*

## Structure

`TagGroupsJsonRequest1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TagGroupsJsonRequest1;
import java.io.IOException;

TagGroupsJsonRequest1 tagGroupsJsonRequest1 = new TagGroupsJsonRequest1.Builder()
    .name("name4")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

