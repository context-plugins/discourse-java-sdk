
# Actions Summary 8

## Structure

`ActionsSummary8`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Count` | `int` | Required | - | int getCount() | setCount(int count) |
| `Hidden` | `boolean` | Required | - | boolean getHidden() | setHidden(boolean hidden) |
| `CanAct` | `boolean` | Required | - | boolean getCanAct() | setCanAct(boolean canAct) |

## Example

```java
import com.example.discourse.models.ActionsSummary8;

ActionsSummary8 actionsSummary8 = new ActionsSummary8.Builder(
    8,
    164,
    false,
    false
)
.build();
```

