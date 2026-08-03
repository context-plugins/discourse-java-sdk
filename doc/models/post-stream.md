
# Post Stream

*This model accepts additional fields of type Object.*

## Structure

`PostStream`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Posts` | [`List<Post3>`](../../doc/models/post-3.md) | Optional | - | List<Post3> getPosts() | setPosts(List<Post3> posts) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Post3;
import com.example.discourse.models.PostStream;
import java.io.IOException;
import java.util.Arrays;

PostStream postStream = new PostStream.Builder()
    .posts(Arrays.asList(
        new Post3.Builder()
            .id(64)
            .name("name6")
            .username("username6")
            .avatarTemplate("avatar_template6")
            .createdAt("created_at4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
        new Post3.Builder()
            .id(64)
            .name("name6")
            .username("username6")
            .avatarTemplate("avatar_template6")
            .createdAt("created_at4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
    ))
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

