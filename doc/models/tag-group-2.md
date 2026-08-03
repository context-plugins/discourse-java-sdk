
# Tag Group 2

*This model accepts additional fields of type Object.*

## Structure

`TagGroup2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `TagNames` | `List<Object>` | Optional | - | List<Object> getTagNames() | setTagNames(List<Object> tagNames) |
| `ParentTagName` | `List<Object>` | Optional | - | List<Object> getParentTagName() | setParentTagName(List<Object> parentTagName) |
| `OnePerTopic` | `Boolean` | Optional | - | Boolean getOnePerTopic() | setOnePerTopic(Boolean onePerTopic) |
| `Permissions` | [`Permissions2`](../../doc/models/permissions-2.md) | Optional | - | Permissions2 getPermissions() | setPermissions(Permissions2 permissions) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TagGroup2;
import java.io.IOException;
import java.util.Arrays;

TagGroup2 tagGroup2 = new TagGroup2.Builder()
    .id(112)
    .name("name2")
    .tagNames(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
    .parentTagName(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
    .onePerTopic(false)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

