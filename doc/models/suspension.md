
# Suspension

## Structure

`Suspension`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `SuspendReason` | `String` | Required | - | String getSuspendReason() | setSuspendReason(String suspendReason) |
| `FullSuspendReason` | `String` | Required | - | String getFullSuspendReason() | setFullSuspendReason(String fullSuspendReason) |
| `SuspendedTill` | `String` | Required | - | String getSuspendedTill() | setSuspendedTill(String suspendedTill) |
| `SuspendedAt` | `String` | Required | - | String getSuspendedAt() | setSuspendedAt(String suspendedAt) |
| `SuspendedBy` | [`SuspendedBy`](../../doc/models/suspended-by.md) | Required | - | SuspendedBy getSuspendedBy() | setSuspendedBy(SuspendedBy suspendedBy) |

## Example

```java
import com.example.discourse.models.SuspendedBy;
import com.example.discourse.models.Suspension;

Suspension suspension = new Suspension.Builder(
    "suspend_reason4",
    "full_suspend_reason6",
    "suspended_till4",
    "suspended_at8",
    new SuspendedBy.Builder(
        146,
        "username4",
        "name4",
        "avatar_template6"
    )
    .build()
)
.build();
```

