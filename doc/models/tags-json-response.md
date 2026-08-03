
# Tags Json Response

*This model accepts additional fields of type Object.*

## Structure

`TagsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Tags` | [`List<Tag3>`](../../doc/models/tag-3.md) | Optional | - | List<Tag3> getTags() | setTags(List<Tag3> tags) |
| `Extras` | [`Extras3`](../../doc/models/extras-3.md) | Optional | - | Extras3 getExtras() | setExtras(Extras3 extras) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extras3;
import com.example.discourse.models.Tag3;
import com.example.discourse.models.TagsJsonResponse;
import java.io.IOException;
import java.util.Arrays;

TagsJsonResponse tagsJsonResponse = new TagsJsonResponse.Builder()
    .tags(Arrays.asList(
        new Tag3.Builder()
            .id(26)
            .text("text0")
            .name("name0")
            .count(110)
            .pmCount(76)
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
        new Tag3.Builder()
            .id(26)
            .text("text0")
            .name("name0")
            .count(110)
            .pmCount(76)
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
        new Tag3.Builder()
            .id(26)
            .text("text0")
            .name("name0")
            .count(110)
            .pmCount(76)
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
    ))
    .extras(new Extras3.Builder()
        .categories(Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ))
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

