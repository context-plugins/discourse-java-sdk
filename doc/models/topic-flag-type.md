
# Topic Flag Type

## Structure

`TopicFlagType`

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
import com.example.discourse.models.TopicFlagType;
import java.io.IOException;
import java.util.Arrays;

TopicFlagType topicFlagType = new TopicFlagType.Builder(
    196,
    "name_key6",
    "name2",
    "description2",
    "short_description8",
    false,
    false,
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    false,
    false
)
.position(226)
.system(false)
.build();
```

