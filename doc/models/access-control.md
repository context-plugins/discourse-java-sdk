
# Access Control

## Structure

`AccessControl`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `MandatoryAcl` | `Object` | Required | - | Object getMandatoryAcl() | setMandatoryAcl(Object mandatoryAcl) |
| `BannedAcl` | `Object` | Required | - | Object getBannedAcl() | setBannedAcl(Object bannedAcl) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.AccessControl;
import java.io.IOException;

AccessControl accessControl = new AccessControl.Builder(
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
)
.build();
```

