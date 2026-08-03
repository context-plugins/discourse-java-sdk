
# Group 5

## Structure

`Group5`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `FullName` | `String` | Optional | - | String getFullName() | setFullName(String fullName) |
| `DisplayName` | `String` | Optional | - | String getDisplayName() | setDisplayName(String displayName) |
| `FlairUrl` | `String` | Required | - | String getFlairUrl() | setFlairUrl(String flairUrl) |
| `FlairBgColor` | `String` | Required | - | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `FlairColor` | `String` | Required | - | String getFlairColor() | setFlairColor(String flairColor) |
| `Automatic` | `boolean` | Required | - | boolean getAutomatic() | setAutomatic(boolean automatic) |

## Example

```java
import com.example.discourse.models.Group5;

Group5 group5 = new Group5.Builder(
    32,
    "name8",
    "flair_url8",
    "flair_bg_color2",
    "flair_color8",
    false
)
.fullName("full_name4")
.displayName("display_name8")
.build();
```

