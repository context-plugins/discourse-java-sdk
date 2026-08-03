
# Penalty Counts

## Structure

`PenaltyCounts`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Silenced` | `int` | Required | - | int getSilenced() | setSilenced(int silenced) |
| `Suspended` | `int` | Required | - | int getSuspended() | setSuspended(int suspended) |

## Example

```java
import com.example.discourse.models.PenaltyCounts;

PenaltyCounts penaltyCounts = new PenaltyCounts.Builder(
    198,
    224
)
.build();
```

