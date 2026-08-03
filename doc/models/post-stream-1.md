
# Post Stream 1

## Structure

`PostStream1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Posts` | [`List<Post4>`](../../doc/models/post-4.md) | Required | - | List<Post4> getPosts() | setPosts(List<Post4> posts) |
| `Stream` | `List<Object>` | Required | - | List<Object> getStream() | setStream(List<Object> stream) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.LinkCount;
import com.example.discourse.models.Post4;
import com.example.discourse.models.PostStream1;
import java.io.IOException;
import java.util.Arrays;

PostStream1 postStream1 = new PostStream1.Builder(
    Arrays.asList(
        new Post4.Builder(
            64,
            "name6",
            "username6",
            "avatar_template6",
            "created_at4",
            "cooked8",
            216,
            210,
            "updated_at2",
            154,
            "reply_to_post_number2",
            78,
            6,
            238,
            102,
            182.76D,
            false,
            2,
            "topic_slug6",
            "display_username6",
            "primary_group_name4",
            "flair_name0",
            "flair_url6",
            "flair_bg_color0",
            "flair_color0",
            36,
            false,
            false,
            false,
            false,
            Arrays.asList(
                new LinkCount.Builder(
                    "url4",
                    false,
                    false,
                    "title6",
                    220
                )
                .build()
            ),
            false,
            "user_title0",
            false,
            Arrays.asList(
                new ActionsSummary.Builder(
                    218,
                    false
                )
                .build()
            ),
            false,
            false,
            false,
            160,
            false,
            48,
            "deleted_at4",
            false,
            "edit_reason4",
            false,
            false,
            138,
            40,
            190
        )
        .canSeeHiddenPost(false)
        .build()
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.build();
```

