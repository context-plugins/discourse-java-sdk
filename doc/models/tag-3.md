
# Tag 3

*This model accepts additional fields of type Object.*

## Structure

`Tag3`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Text` | `String` | Optional | - | String getText() | setText(String text) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `Count` | `Integer` | Optional | - | Integer getCount() | setCount(Integer count) |
| `PmCount` | `Integer` | Optional | - | Integer getPmCount() | setPmCount(Integer pmCount) |
| `TargetTag` | `String` | Optional | - | String getTargetTag() | setTargetTag(String targetTag) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Tag3;
import java.io.IOException;

Tag3 tag3 = new Tag3.Builder()
    .id(200)
    .text("text6")
    .name("name4")
    .count(228)
    .pmCount(250)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

