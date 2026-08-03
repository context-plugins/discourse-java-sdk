
# User Tips

## Structure

`UserTips`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `FirstNotification` | `int` | Required | - | int getFirstNotification() | setFirstNotification(int firstNotification) |
| `TopicTimeline` | `int` | Required | - | int getTopicTimeline() | setTopicTimeline(int topicTimeline) |
| `PostMenu` | `int` | Required | - | int getPostMenu() | setPostMenu(int postMenu) |
| `TopicNotificationLevels` | `int` | Required | - | int getTopicNotificationLevels() | setTopicNotificationLevels(int topicNotificationLevels) |
| `SuggestedTopics` | `int` | Required | - | int getSuggestedTopics() | setSuggestedTopics(int suggestedTopics) |

## Example

```java
import com.example.discourse.models.UserTips;

UserTips userTips = new UserTips.Builder(
    192,
    48,
    222,
    0,
    56
)
.build();
```

