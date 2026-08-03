
# Admin Badges Json Request 1

## Structure

`AdminBadgesJsonRequest1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | The name for the new badge. | String getName() | setName(String name) |
| `BadgeTypeId` | `int` | Required | The ID for the badge type. 1 for Gold, 2 for Silver,<br>3 for Bronze. | int getBadgeTypeId() | setBadgeTypeId(int badgeTypeId) |

## Example

```java
import com.example.discourse.models.AdminBadgesJsonRequest1;

AdminBadgesJsonRequest1 adminBadgesJsonRequest1 = new AdminBadgesJsonRequest1.Builder(
    "name2",
    138
)
.build();
```

