
# User Theme

## Structure

`UserTheme`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `ThemeId` | `int` | Required | - | int getThemeId() | setThemeId(int themeId) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Default` | `boolean` | Required | - | boolean getDefault() | setDefault(boolean mDefault) |
| `ColorSchemeId` | `Integer` | Required | - | Integer getColorSchemeId() | setColorSchemeId(Integer colorSchemeId) |
| `DarkColorSchemeId` | `Integer` | Optional | - | Integer getDarkColorSchemeId() | setDarkColorSchemeId(Integer darkColorSchemeId) |
| `OnlyThemeColorSchemes` | `Boolean` | Optional | - | Boolean getOnlyThemeColorSchemes() | setOnlyThemeColorSchemes(Boolean onlyThemeColorSchemes) |

## Example

```java
import com.example.discourse.models.UserTheme;

UserTheme userTheme = new UserTheme.Builder(
    224,
    "name8",
    false,
    8
)
.darkColorSchemeId(124)
.onlyThemeColorSchemes(false)
.build();
```

