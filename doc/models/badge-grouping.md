
# Badge Grouping

## Structure

`BadgeGrouping`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `Position` | `int` | Required | - | int getPosition() | setPosition(int position) |
| `System` | `boolean` | Required | - | boolean getSystem() | setSystem(boolean system) |

## Example

```java
import com.example.discourse.models.BadgeGrouping;

BadgeGrouping badgeGrouping = new BadgeGrouping.Builder(
    228,
    "name2",
    "description2",
    2,
    false
)
.build();
```

