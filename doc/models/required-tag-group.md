
# Required Tag Group

## Structure

`RequiredTagGroup`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `MinCount` | `int` | Required | - | int getMinCount() | setMinCount(int minCount) |

## Example

```java
import com.example.discourse.models.RequiredTagGroup;

RequiredTagGroup requiredTagGroup = new RequiredTagGroup.Builder(
    "name6",
    232
)
.build();
```

