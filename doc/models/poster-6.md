
# Poster 6

*This model accepts additional fields of type Object.*

## Structure

`Poster6`

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
import com.example.discourse.models.Poster6;
import java.io.IOException;

Poster6 poster6 = new Poster6.Builder()
    .extras("extras6")
    .description("description2")
    .userId(186)
    .primaryGroupId(102)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

