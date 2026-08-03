
# T Notifications Json Response

*This model accepts additional fields of type Object.*

## Structure

`TNotificationsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Optional | - | String getSuccess() | setSuccess(String success) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TNotificationsJsonResponse;
import java.io.IOException;

TNotificationsJsonResponse tNotificationsJsonResponse = new TNotificationsJsonResponse.Builder()
    .success("OK")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

