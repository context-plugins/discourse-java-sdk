
# Badge Type

## Structure

`BadgeType`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `SortOrder` | `int` | Required | - | int getSortOrder() | setSortOrder(int sortOrder) |

## Example

```java
import com.example.discourse.models.BadgeType;

BadgeType badgeType = new BadgeType.Builder(
    78,
    "name4",
    44
)
.build();
```

