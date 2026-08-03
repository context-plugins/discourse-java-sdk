
# T Posts Json Response

*This model accepts additional fields of type Object.*

## Structure

`TPostsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `PostStream` | [`PostStream`](../../doc/models/post-stream.md) | Optional | - | PostStream getPostStream() | setPostStream(PostStream postStream) |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Post3;
import com.example.discourse.models.PostStream;
import com.example.discourse.models.TPostsJsonResponse;
import java.io.IOException;
import java.util.Arrays;

TPostsJsonResponse tPostsJsonResponse = new TPostsJsonResponse.Builder()
    .postStream(new PostStream.Builder()
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
        .build())
    .id(142)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

