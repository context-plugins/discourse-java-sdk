
# Silence

## Structure

`Silence`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Silenced` | `boolean` | Required | - | boolean getSilenced() | setSilenced(boolean silenced) |
| `SilenceReason` | `String` | Required | - | String getSilenceReason() | setSilenceReason(String silenceReason) |
| `FullSilenceReason` | `String` | Required | - | String getFullSilenceReason() | setFullSilenceReason(String fullSilenceReason) |
| `SilencedTill` | `String` | Required | - | String getSilencedTill() | setSilencedTill(String silencedTill) |
| `SilencedAt` | `String` | Required | - | String getSilencedAt() | setSilencedAt(String silencedAt) |
| `SilencedBy` | [`SilencedBy`](../../doc/models/silenced-by.md) | Required | - | SilencedBy getSilencedBy() | setSilencedBy(SilencedBy silencedBy) |

## Example

```java
import com.example.discourse.models.Silence;
import com.example.discourse.models.SilencedBy;

Silence silence = new Silence.Builder(
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
.build();
```

