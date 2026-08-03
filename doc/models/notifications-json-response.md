
# Notifications Json Response

*This model accepts additional fields of type Object.*

## Structure

`NotificationsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Notifications` | [`List<Notification>`](../../doc/models/notification.md) | Optional | - | List<Notification> getNotifications() | setNotifications(List<Notification> notifications) |
| `TotalRowsNotifications` | `Integer` | Optional | - | Integer getTotalRowsNotifications() | setTotalRowsNotifications(Integer totalRowsNotifications) |
| `SeenNotificationId` | `Integer` | Optional | - | Integer getSeenNotificationId() | setSeenNotificationId(Integer seenNotificationId) |
| `LoadMoreNotifications` | `String` | Optional | - | String getLoadMoreNotifications() | setLoadMoreNotifications(String loadMoreNotifications) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Notification;
import com.example.discourse.models.NotificationsJsonResponse;
import java.io.IOException;
import java.util.Arrays;

NotificationsJsonResponse notificationsJsonResponse = new NotificationsJsonResponse.Builder()
    .notifications(Arrays.asList(
        new Notification.Builder()
            .id(86)
            .userId(182)
            .notificationType(106)
            .read(false)
            .createdAt("created_at0")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
    ))
    .totalRowsNotifications(210)
    .seenNotificationId(238)
    .loadMoreNotifications("load_more_notifications6")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

