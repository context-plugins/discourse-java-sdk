
# Posts Json Response

## Structure

`PostsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `LatestPosts` | [`List<LatestPost>`](../../doc/models/latest-post.md) | Required | - | List<LatestPost> getLatestPosts() | setLatestPosts(List<LatestPost> latestPosts) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.LatestPost;
import com.example.discourse.models.PostsJsonResponse;
import java.io.IOException;
import java.util.Arrays;

PostsJsonResponse postsJsonResponse = new PostsJsonResponse.Builder(
    Arrays.asList(
        new LatestPost.Builder(
            36,
            "name6",
            "username4",
            "avatar_template4",
            "created_at4",
            "cooked2",
            188,
            74,
            174,
            "updated_at8",
            126,
            "reply_to_post_number2",
            50,
            34,
            46,
            182,
            113.36D,
            false,
            26,
            "topic_slug6",
            "topic_title2",
            "topic_html_title4",
            226,
            "display_username6",
            "primary_group_name4",
            "flair_name0",
            "flair_url6",
            "flair_bg_color0",
            "flair_color0",
            "flair_group_id4",
            Arrays.asList(
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
            ),
            8,
            false,
            false,
            false,
            false,
            false,
            "user_title0",
            false,
            "raw0",
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
            132,
            false,
            20,
            "deleted_at4",
            false,
            "edit_reason4",
            false,
            false,
            "excerpt8",
            false,
            "reviewable_id4",
            244,
            218,
            "post_url2"
        )
        .build()
    )
)
.build();
```

