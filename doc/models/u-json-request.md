
# U Json Request

## Structure

`UJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `ExternalIds` | `Object` | Optional | - | Object getExternalIds() | setExternalIds(Object externalIds) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UJsonRequest;
import java.io.IOException;

UJsonRequest uJsonRequest = new UJsonRequest.Builder()
    .name("name8")
    .externalIds(ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

