
# Category Localization

*This model accepts additional fields of type Object.*

## Structure

`CategoryLocalization`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | The unique identifier for an existing localization.<br>Must be included otherwise the record will be deleted. | Integer getId() | setId(Integer id) |
| `Locale` | `String` | Required | The locale for the localization, e.g., 'en',<br>'zh_CN'. Locale should be in the list of SiteSetting.content_localization_supported_locales. | String getLocale() | setLocale(String locale) |
| `Name` | `String` | Required | The name of the category in the specified locale. | String getName() | setName(String name) |
| `Description` | `String` | Optional | The description excerpt of the category in the<br>specified locale. | String getDescription() | setDescription(String description) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.CategoryLocalization;
import java.io.IOException;

CategoryLocalization categoryLocalization = new CategoryLocalization.Builder(
    "locale6",
    "name8"
)
.id(112)
.description("description8")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

