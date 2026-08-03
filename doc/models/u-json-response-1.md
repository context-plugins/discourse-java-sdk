
# U Json Response 1

## Structure

`UJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |
| `User` | `Object` | Required | - | Object getUser() | setUser(Object user) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UJsonResponse1;
import java.io.IOException;

UJsonResponse1 uJsonResponse1 = new UJsonResponse1.Builder(
    "success0",
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
)
.build();
```

