
# Posts Locked Json Response

*This model accepts additional fields of type Object.*

## Structure

`PostsLockedJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Locked` | `boolean` | Required | Whether the post is locked | boolean getLocked() | setLocked(boolean locked) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.PostsLockedJsonResponse;
import java.io.IOException;

PostsLockedJsonResponse postsLockedJsonResponse = new PostsLockedJsonResponse.Builder(
    false
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

