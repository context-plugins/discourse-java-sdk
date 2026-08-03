
# Extras

## Structure

`Extras`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `VisibleGroupNames` | `List<Object>` | Required | - | List<Object> getVisibleGroupNames() | setVisibleGroupNames(List<Object> visibleGroupNames) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extras;
import java.io.IOException;
import java.util.Arrays;

Extras extras = new Extras.Builder(
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.build();
```

