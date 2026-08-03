
# Penalty Counts 1

## Structure

`PenaltyCounts1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Silenced` | `int` | Required | - | int getSilenced() | setSilenced(int silenced) |
| `Suspended` | `int` | Required | - | int getSuspended() | setSuspended(int suspended) |
| `Total` | `int` | Required | - | int getTotal() | setTotal(int total) |

## Example

```java
import com.example.discourse.models.PenaltyCounts1;

PenaltyCounts1 penaltyCounts1 = new PenaltyCounts1.Builder(
    140,
    142,
    98
)
.build();
```

