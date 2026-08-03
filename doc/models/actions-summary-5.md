
# Actions Summary 5

*This model accepts additional fields of type Object.*

## Structure

`ActionsSummary5`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | ID of the action type (e.g., 2 for like) | Integer getId() | setId(Integer id) |
| `Count` | `Integer` | Optional | Number of times this action has been performed | Integer getCount() | setCount(Integer count) |
| `Acted` | `Boolean` | Optional | Whether the current user has performed this<br>action | Boolean getActed() | setActed(Boolean acted) |
| `CanUndo` | `Boolean` | Optional | Whether the current user can undo this action | Boolean getCanUndo() | setCanUndo(Boolean canUndo) |
| `CanAct` | `Boolean` | Optional | Whether the current user can perform this action | Boolean getCanAct() | setCanAct(Boolean canAct) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary5;
import java.io.IOException;

ActionsSummary5 actionsSummary5 = new ActionsSummary5.Builder()
    .id(252)
    .count(176)
    .acted(false)
    .canUndo(false)
    .canAct(false)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

