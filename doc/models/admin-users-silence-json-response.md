
# Admin Users Silence Json Response

## Structure

`AdminUsersSilenceJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Silence` | [`Silence`](../../doc/models/silence.md) | Required | - | Silence getSilence() | setSilence(Silence silence) |

## Example

```java
import com.example.discourse.models.AdminUsersSilenceJsonResponse;
import com.example.discourse.models.Silence;
import com.example.discourse.models.SilencedBy;

AdminUsersSilenceJsonResponse adminUsersSilenceJsonResponse = new AdminUsersSilenceJsonResponse.Builder(
    new Silence.Builder(
        false,
        "silence_reason2",
        "full_silence_reason0",
        "silenced_till2",
        "silenced_at0",
        new SilencedBy.Builder(
            46,
            "username6",
            "name4",
            "avatar_template6"
        )
        .build()
    )
    .build()
)
.build();
```

