
# Posts Json Request 2

## Structure

`PostsJsonRequest2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `ForceDestroy` | `Boolean` | Optional | The `SiteSetting.can_permanently_delete` needs to be<br>enabled first before this param can be used. Also this endpoint<br>needs to be called first without `force_destroy` and then followed<br>up with a second call 5 minutes later with `force_destroy` to<br>permanently delete. | Boolean getForceDestroy() | setForceDestroy(Boolean forceDestroy) |

## Example

```java
import com.example.discourse.models.PostsJsonRequest2;

PostsJsonRequest2 postsJsonRequest2 = new PostsJsonRequest2.Builder()
    .forceDestroy(true)
    .build();
```

