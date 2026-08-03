
# Tag 4

*This model accepts additional fields of type Object.*

## Structure

`Tag4`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `TopicCount` | `Integer` | Optional | - | Integer getTopicCount() | setTopicCount(Integer topicCount) |
| `Staff` | `Boolean` | Optional | - | Boolean getStaff() | setStaff(Boolean staff) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Tag4;
import java.io.IOException;

Tag4 tag4 = new Tag4.Builder()
    .id(190)
    .name("name8")
    .topicCount(90)
    .staff(false)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

