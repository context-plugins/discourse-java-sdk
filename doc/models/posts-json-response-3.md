
# Posts Json Response 3

## Structure

`PostsJsonResponse3`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Post` | [`Post2`](../../doc/models/post-2.md) | Required | - | Post2 getPost() | setPost(Post2 post) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.Post2;
import com.example.discourse.models.PostsJsonResponse3;
import java.io.IOException;
import java.util.Arrays;

PostsJsonResponse3 postsJsonResponse3 = new PostsJsonResponse3.Builder(
    new Post2.Builder(
        236,
        "username0",
        "avatar_template0",
        "created_at8",
        "cooked8",
        132,
        130,
        118,
        "updated_at6",
        70,
        "reply_to_post_number6",
        250,
        90,
        102,
        18,
        253.6D,
        false,
        82,
        "topic_slug0",
        "primary_group_name8",
        "flair_name4",
        "flair_url0",
        "flair_bg_color4",
        "flair_color4",
        208,
        false,
        false,
        false,
        false,
        "user_title4",
        false,
        "raw4",
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
        76,
        122,
        false,
        220,
        "deleted_at8",
        false,
        "edit_reason8",
        false,
        false,
        54,
        212,
        18,
        "post_url2"
    )
    .flairGroupId(30)
    .badgesGranted(Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ))
    .canSeeHiddenPost(false)
    .postLocalizations(Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ))
    .mentionedUsers(Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ))
    .build()
)
.build();
```

