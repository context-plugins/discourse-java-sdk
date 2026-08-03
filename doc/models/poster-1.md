
# Poster 1

*This model accepts additional fields of type Object.*

## Structure

`Poster1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Extras` | `String` | Optional | - | String getExtras() | setExtras(String extras) |
| `Description` | `String` | Optional | - | String getDescription() | setDescription(String description) |
| `UserId` | `Integer` | Optional | - | Integer getUserId() | setUserId(Integer userId) |
| `PrimaryGroupId` | `Integer` | Optional | - | Integer getPrimaryGroupId() | setPrimaryGroupId(Integer primaryGroupId) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Poster1;
import java.io.IOException;

Poster1 poster1 = new Poster1.Builder()
    .extras("extras2")
    .description("description8")
    .userId(230)
    .primaryGroupId(146)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

