
# Post

## Structure

`Post`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `PostNumber` | `int` | Required | - | int getPostNumber() | setPostNumber(int postNumber) |
| `Url` | `String` | Required | - | String getUrl() | setUrl(String url) |
| `CategorySlug` | `String` | Required | - | String getCategorySlug() | setCategorySlug(String categorySlug) |
| `Topic` | [`Topic`](../../doc/models/topic.md) | Required | - | Topic getTopic() | setTopic(Topic topic) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Post;
import com.example.discourse.models.Topic;
import java.io.IOException;
import java.util.Arrays;

Post post = new Post.Builder(
    236,
    132,
    "url4",
    "category_slug4",
    new Topic.Builder(
        54,
        "title4",
        Arrays.asList(
            "tags3"
        ),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        "slug2"
    )
    .build()
)
.build();
```

