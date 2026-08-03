
# Group User

## Structure

`GroupUser`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `GroupId` | `int` | Required | - | int getGroupId() | setGroupId(int groupId) |
| `UserId` | `int` | Required | - | int getUserId() | setUserId(int userId) |
| `NotificationLevel` | `int` | Required | - | int getNotificationLevel() | setNotificationLevel(int notificationLevel) |
| `Owner` | `Boolean` | Optional | - | Boolean getOwner() | setOwner(Boolean owner) |

## Example

```java
import com.example.discourse.models.GroupUser;

GroupUser groupUser = new GroupUser.Builder(
    158,
    22,
    22
)
.owner(false)
.build();
```

