
# Topic

## Structure

`Topic`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `Tags` | `List<String>` | Required | - | List<String> getTags() | setTags(List<String> tags) |
| `TagsDescriptions` | `Object` | Required | - | Object getTagsDescriptions() | setTagsDescriptions(Object tagsDescriptions) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Topic;
import java.io.IOException;
import java.util.Arrays;

Topic topic = new Topic.Builder(
    54,
    "title4",
    Arrays.asList(
        "tags3"
    ),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    "slug2"
)
.build();
```

