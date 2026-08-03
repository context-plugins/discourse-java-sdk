
# Participant

*This model accepts additional fields of type Object.*

## Structure

`Participant`

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
import com.example.discourse.models.Participant;
import java.io.IOException;

Participant participant = new Participant.Builder()
    .extras("extras0")
    .description("description6")
    .userId(152)
    .primaryGroupId(68)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

