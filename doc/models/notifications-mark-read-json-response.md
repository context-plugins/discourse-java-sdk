
# Notifications Mark Read Json Response

*This model accepts additional fields of type Object.*

## Structure

`NotificationsMarkReadJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Optional | - | String getSuccess() | setSuccess(String success) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.NotificationsMarkReadJsonResponse;
import java.io.IOException;

NotificationsMarkReadJsonResponse notificationsMarkReadJsonResponse = new NotificationsMarkReadJsonResponse.Builder()
    .success("success8")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

