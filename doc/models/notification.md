
# Notification

*This model accepts additional fields of type Object.*

## Structure

`Notification`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `UserId` | `Integer` | Optional | - | Integer getUserId() | setUserId(Integer userId) |
| `NotificationType` | `Integer` | Optional | - | Integer getNotificationType() | setNotificationType(Integer notificationType) |
| `Read` | `Boolean` | Optional | - | Boolean getRead() | setRead(Boolean read) |
| `CreatedAt` | `String` | Optional | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `PostNumber` | `Integer` | Optional | - | Integer getPostNumber() | setPostNumber(Integer postNumber) |
| `TopicId` | `Integer` | Optional | - | Integer getTopicId() | setTopicId(Integer topicId) |
| `Slug` | `String` | Optional | - | String getSlug() | setSlug(String slug) |
| `Data` | [`Data`](../../doc/models/data.md) | Optional | - | Data getData() | setData(Data data) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Notification;
import java.io.IOException;

Notification notification = new Notification.Builder()
    .id(88)
    .userId(184)
    .notificationType(108)
    .read(false)
    .createdAt("created_at0")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

