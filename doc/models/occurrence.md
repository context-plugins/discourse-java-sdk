
# Occurrence

## Structure

`Occurrence`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `StartsAt` | `String` | Required | - | String getStartsAt() | setStartsAt(String startsAt) |
| `EndsAt` | `String` | Required | - | String getEndsAt() | setEndsAt(String endsAt) |

## Example

```java
import com.example.discourse.models.Occurrence;

Occurrence occurrence = new Occurrence.Builder(
    "starts_at2",
    "ends_at6"
)
.build();
```

