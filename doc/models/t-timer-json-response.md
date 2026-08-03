
# T Timer Json Response

*This model accepts additional fields of type Object.*

## Structure

`TTimerJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Optional | - | String getSuccess() | setSuccess(String success) |
| `ExecuteAt` | `String` | Optional | - | String getExecuteAt() | setExecuteAt(String executeAt) |
| `Duration` | `String` | Optional | - | String getDuration() | setDuration(String duration) |
| `BasedOnLastPost` | `Boolean` | Optional | - | Boolean getBasedOnLastPost() | setBasedOnLastPost(Boolean basedOnLastPost) |
| `Closed` | `Boolean` | Optional | - | Boolean getClosed() | setClosed(Boolean closed) |
| `CategoryId` | `Integer` | Optional | - | Integer getCategoryId() | setCategoryId(Integer categoryId) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TTimerJsonResponse;
import java.io.IOException;

TTimerJsonResponse tTimerJsonResponse = new TTimerJsonResponse.Builder()
    .success("OK")
    .executeAt("execute_at6")
    .duration("duration8")
    .basedOnLastPost(false)
    .closed(false)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

