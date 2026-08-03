
# Post Action Type

## Structure

`PostActionType`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Required | - | Integer getId() | setId(Integer id) |
| `NameKey` | `String` | Required | - | String getNameKey() | setNameKey(String nameKey) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `ShortDescription` | `String` | Required | - | String getShortDescription() | setShortDescription(String shortDescription) |
| `IsFlag` | `boolean` | Required | - | boolean getIsFlag() | setIsFlag(boolean isFlag) |
| `RequireMessage` | `boolean` | Required | - | boolean getRequireMessage() | setRequireMessage(boolean requireMessage) |
| `Enabled` | `boolean` | Required | - | boolean getEnabled() | setEnabled(boolean enabled) |
| `AppliesTo` | `List<Object>` | Required | - | List<Object> getAppliesTo() | setAppliesTo(List<Object> appliesTo) |
| `IsUsed` | `boolean` | Required | - | boolean getIsUsed() | setIsUsed(boolean isUsed) |
| `Position` | `Integer` | Optional | - | Integer getPosition() | setPosition(Integer position) |
| `AutoActionType` | `boolean` | Required | - | boolean getAutoActionType() | setAutoActionType(boolean autoActionType) |
| `System` | `Boolean` | Optional | - | Boolean getSystem() | setSystem(Boolean system) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.PostActionType;
import java.io.IOException;
import java.util.Arrays;

PostActionType postActionType = new PostActionType.Builder(
    228,
    "name_key8",
    "name4",
    "description4",
    "short_description0",
    false,
    false,
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    false,
    false
)
.position(2)
.system(false)
.build();
```

