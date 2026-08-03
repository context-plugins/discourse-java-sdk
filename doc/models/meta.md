
# Meta

## Structure

`Meta`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Total` | `int` | Required | - | int getTotal() | setTotal(int total) |
| `Limit` | `int` | Required | - | int getLimit() | setLimit(int limit) |
| `Offset` | `int` | Required | - | int getOffset() | setOffset(int offset) |

## Example

```java
import com.example.discourse.models.Meta;

Meta meta = new Meta.Builder(
    36,
    126,
    222
)
.build();
```

