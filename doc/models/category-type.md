
# Category Type

## Structure

`CategoryType`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `String` | Required | - | String getId() | setId(String id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `Icon` | `String` | Required | - | String getIcon() | setIcon(String icon) |
| `Available` | `boolean` | Required | - | boolean getAvailable() | setAvailable(boolean available) |
| `Visible` | `boolean` | Required | - | boolean getVisible() | setVisible(boolean visible) |
| `ConfigurationSchema` | `Object` | Required | - | Object getConfigurationSchema() | setConfigurationSchema(Object configurationSchema) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.CategoryType;
import java.io.IOException;

CategoryType categoryType = new CategoryType.Builder(
    "id6",
    "name6",
    "title8",
    "description4",
    "icon2",
    false,
    false,
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
)
.build();
```

