
# Extras 2

## Structure

`Extras2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `TypeFilters` | `List<Object>` | Required | - | List<Object> getTypeFilters() | setTypeFilters(List<Object> typeFilters) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extras2;
import java.io.IOException;
import java.util.Arrays;

Extras2 extras2 = new Extras2.Builder(
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.build();
```

