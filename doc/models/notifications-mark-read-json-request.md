
# Notifications Mark Read Json Request

*This model accepts additional fields of type Object.*

## Structure

`NotificationsMarkReadJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | (optional) Leave off to mark all notifications as<br>read | Integer getId() | setId(Integer id) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.NotificationsMarkReadJsonRequest;
import java.io.IOException;

NotificationsMarkReadJsonRequest notificationsMarkReadJsonRequest = new NotificationsMarkReadJsonRequest.Builder()
    .id(62)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

