
# T Notifications Json Request

*This model accepts additional fields of type Object.*

## Structure

`TNotificationsJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `NotificationLevel` | [`NotificationLevel`](../../doc/models/notification-level.md) | Required | - | NotificationLevel getNotificationLevel() | setNotificationLevel(NotificationLevel notificationLevel) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.NotificationLevel;
import com.example.discourse.models.TNotificationsJsonRequest;
import java.io.IOException;

TNotificationsJsonRequest tNotificationsJsonRequest = new TNotificationsJsonRequest.Builder(
    NotificationLevel.ENUM_2
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

