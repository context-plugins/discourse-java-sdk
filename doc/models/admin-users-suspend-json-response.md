
# Admin Users Suspend Json Response

## Structure

`AdminUsersSuspendJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Suspension` | [`Suspension`](../../doc/models/suspension.md) | Required | - | Suspension getSuspension() | setSuspension(Suspension suspension) |

## Example

```java
import com.example.discourse.models.AdminUsersSuspendJsonResponse;
import com.example.discourse.models.SuspendedBy;
import com.example.discourse.models.Suspension;

AdminUsersSuspendJsonResponse adminUsersSuspendJsonResponse = new AdminUsersSuspendJsonResponse.Builder(
    new Suspension.Builder(
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
    .build()
)
.build();
```

