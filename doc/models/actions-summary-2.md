
# Actions Summary 2

## Structure

`ActionsSummary2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | `2`: like, `3`, `4`, `6`, `7`, `8`: flag | int getId() | setId(int id) |
| `Count` | `Integer` | Optional | - | Integer getCount() | setCount(Integer count) |
| `Acted` | `Boolean` | Optional | - | Boolean getActed() | setActed(Boolean acted) |
| `CanUndo` | `Boolean` | Optional | - | Boolean getCanUndo() | setCanUndo(Boolean canUndo) |
| `CanAct` | `Boolean` | Optional | - | Boolean getCanAct() | setCanAct(Boolean canAct) |

## Example

```java
import com.example.discourse.models.ActionsSummary2;

ActionsSummary2 actionsSummary2 = new ActionsSummary2.Builder(
    64
)
.count(108)
.acted(false)
.canUndo(false)
.canAct(false)
.build();
```

