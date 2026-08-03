
# Permissions

*This model accepts additional fields of type Object.*

## Structure

`Permissions`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Everyone` | `Integer` | Optional | - | Integer getEveryone() | setEveryone(Integer everyone) |
| `Staff` | `Integer` | Optional | - | Integer getStaff() | setStaff(Integer staff) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Permissions;
import java.io.IOException;

Permissions permissions = new Permissions.Builder()
    .everyone(1)
    .staff(166)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

