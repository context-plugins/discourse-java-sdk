
# Archetype

## Structure

`Archetype`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `String` | Required | - | String getId() | setId(String id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Options` | `List<Object>` | Required | - | List<Object> getOptions() | setOptions(List<Object> options) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Archetype;
import java.io.IOException;
import java.util.Arrays;

Archetype archetype = new Archetype.Builder(
    "id4",
    "name4",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.build();
```

