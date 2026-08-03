
# Tag Group 1

*This model accepts additional fields of type Object.*

## Structure

`TagGroup1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Tags` | [`List<Tag>`](../../doc/models/tag.md) | Required | - | List<Tag> getTags() | setTags(List<Tag> tags) |
| `ParentTag` | [`List<ParentTag>`](../../doc/models/parent-tag.md) | Required | - | List<ParentTag> getParentTag() | setParentTag(List<ParentTag> parentTag) |
| `OnePerTopic` | `boolean` | Required | - | boolean getOnePerTopic() | setOnePerTopic(boolean onePerTopic) |
| `Permissions` | `Object` | Required | - | Object getPermissions() | setPermissions(Object permissions) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ParentTag;
import com.example.discourse.models.Tag;
import com.example.discourse.models.TagGroup1;
import java.io.IOException;
import java.util.Arrays;

TagGroup1 tagGroup1 = new TagGroup1.Builder(
    26,
    "name2",
    Arrays.asList(
        new Tag.Builder(
            26,
            "name0",
            "slug4"
        )
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build()
    ),
    Arrays.asList(
        new ParentTag.Builder(
            110,
            "name2",
            "slug6"
        )
        .build()
    ),
    false,
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

