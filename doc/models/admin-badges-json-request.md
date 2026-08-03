
# Admin Badges Json Request

## Structure

`AdminBadgesJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | The name for the new badge. | String getName() | setName(String name) |
| `BadgeTypeId` | `int` | Required | The ID for the badge type. 1 for Gold, 2 for Silver,<br>3 for Bronze. | int getBadgeTypeId() | setBadgeTypeId(int badgeTypeId) |

## Example

```java
import com.example.discourse.models.AdminBadgesJsonRequest;

AdminBadgesJsonRequest adminBadgesJsonRequest = new AdminBadgesJsonRequest.Builder(
    "name8",
    98
)
.build();
```

