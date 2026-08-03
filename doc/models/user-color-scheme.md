
# User Color Scheme

## Structure

`UserColorScheme`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `IsDark` | `boolean` | Required | - | boolean getIsDark() | setIsDark(boolean isDark) |
| `ThemeId` | `Integer` | Optional | - | Integer getThemeId() | setThemeId(Integer themeId) |
| `Colors` | `List<Object>` | Required | - | List<Object> getColors() | setColors(List<Object> colors) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UserColorScheme;
import java.io.IOException;
import java.util.Arrays;

UserColorScheme userColorScheme = new UserColorScheme.Builder(
    28,
    "name0",
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.themeId(254)
.build();
```

