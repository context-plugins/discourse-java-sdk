
# Tag Group

## Structure

`TagGroup`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Tags` | [`List<Tag>`](../../doc/models/tag.md) | Required | - | List<Tag> getTags() | setTags(List<Tag> tags) |
| `ParentTag` | [`List<ParentTag>`](../../doc/models/parent-tag.md) | Required | - | List<ParentTag> getParentTag() | setParentTag(List<ParentTag> parentTag) |
| `OnePerTopic` | `boolean` | Required | - | boolean getOnePerTopic() | setOnePerTopic(boolean onePerTopic) |
| `Permissions` | `Map<String, Integer>` | Required | - | Map<String, Integer> getPermissions() | setPermissions(Map<String, Integer> permissions) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ParentTag;
import com.example.discourse.models.Tag;
import com.example.discourse.models.TagGroup;
import java.io.IOException;
import java.util.Arrays;
import java.util.LinkedHashMap;

TagGroup tagGroup = new TagGroup.Builder(
    4,
    "name4",
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
    new LinkedHashMap<String, Integer>() {{
        put("key0", 87);
    }}
)
.build();
```

