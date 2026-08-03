
# Post 1

## Structure

`Post1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Raw` | `String` | Required | - | String getRaw() | setRaw(String raw) |
| `EditReason` | `String` | Optional | - | String getEditReason() | setEditReason(String editReason) |

## Example

```java
import com.example.discourse.models.Post1;

Post1 post1 = new Post1.Builder(
    "raw8"
)
.editReason("edit_reason2")
.build();
```

