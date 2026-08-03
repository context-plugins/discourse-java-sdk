
# Basic Topic

*This model accepts additional fields of type Object.*

## Structure

`BasicTopic`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Title` | `String` | Optional | - | String getTitle() | setTitle(String title) |
| `FancyTitle` | `String` | Optional | - | String getFancyTitle() | setFancyTitle(String fancyTitle) |
| `Slug` | `String` | Optional | - | String getSlug() | setSlug(String slug) |
| `PostsCount` | `Integer` | Optional | - | Integer getPostsCount() | setPostsCount(Integer postsCount) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.BasicTopic;
import java.io.IOException;

BasicTopic basicTopic = new BasicTopic.Builder()
    .id(164)
    .title("title2")
    .fancyTitle("fancy_title6")
    .slug("slug0")
    .postsCount(46)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

