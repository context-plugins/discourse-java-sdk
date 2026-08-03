
# T Timer Json Request

*This model accepts additional fields of type Object.*

## Structure

`TTimerJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Time` | `String` | Optional | - | String getTime() | setTime(String time) |
| `StatusType` | `String` | Optional | - | String getStatusType() | setStatusType(String statusType) |
| `BasedOnLastPost` | `Boolean` | Optional | - | Boolean getBasedOnLastPost() | setBasedOnLastPost(Boolean basedOnLastPost) |
| `CategoryId` | `Integer` | Optional | - | Integer getCategoryId() | setCategoryId(Integer categoryId) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TTimerJsonRequest;
import java.io.IOException;

TTimerJsonRequest tTimerJsonRequest = new TTimerJsonRequest.Builder()
    .time("time0")
    .statusType("status_type2")
    .basedOnLastPost(false)
    .categoryId(18)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

