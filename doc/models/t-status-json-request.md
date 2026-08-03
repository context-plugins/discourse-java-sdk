
# T Status Json Request

*This model accepts additional fields of type Object.*

## Structure

`TStatusJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Status` | [`Status1`](../../doc/models/status-1.md) | Required | - | Status1 getStatus() | setStatus(Status1 status) |
| `Enabled` | [`Enabled`](../../doc/models/enabled.md) | Required | - | Enabled getEnabled() | setEnabled(Enabled enabled) |
| `Until` | `String` | Optional | Only required for `pinned` and `pinned_globally` | String getUntil() | setUntil(String until) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Enabled;
import com.example.discourse.models.Status1;
import com.example.discourse.models.TStatusJsonRequest;
import java.io.IOException;

TStatusJsonRequest tStatusJsonRequest = new TStatusJsonRequest.Builder(
    Status1.PINNED_GLOBALLY,
    Enabled.ENUM_TRUE
)
.until("2030-12-31")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

