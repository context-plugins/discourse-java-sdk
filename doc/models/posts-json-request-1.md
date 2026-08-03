
# Posts Json Request 1

## Structure

`PostsJsonRequest1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Post` | [`Post1`](../../doc/models/post-1.md) | Optional | - | Post1 getPost() | setPost(Post1 post) |
| `BypassBump` | `Boolean` | Optional | Skip bumping the topic when updating the post. Requires<br>staff or TL4 permissions. | Boolean getBypassBump() | setBypassBump(Boolean bypassBump) |

## Example

```java
import com.example.discourse.models.Post1;
import com.example.discourse.models.PostsJsonRequest1;

PostsJsonRequest1 postsJsonRequest1 = new PostsJsonRequest1.Builder()
    .post(new Post1.Builder(
        "raw4"
    )
    .editReason("edit_reason8")
    .build())
    .bypassBump(false)
    .build();
```

