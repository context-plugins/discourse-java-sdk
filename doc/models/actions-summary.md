
# Actions Summary

## Structure

`ActionsSummary`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `CanAct` | `boolean` | Required | - | boolean getCanAct() | setCanAct(boolean canAct) |

## Example

```java
import com.example.discourse.models.ActionsSummary;

ActionsSummary actionsSummary = new ActionsSummary.Builder(
    94,
    false
)
.build();
```

