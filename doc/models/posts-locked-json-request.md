
# Posts Locked Json Request

*This model accepts additional fields of type Object.*

## Structure

`PostsLockedJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Locked` | `String` | Required | Whether to lock the post (true/false) | String getLocked() | setLocked(String locked) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.PostsLockedJsonRequest;
import java.io.IOException;

PostsLockedJsonRequest postsLockedJsonRequest = new PostsLockedJsonRequest.Builder(
    "locked8"
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

