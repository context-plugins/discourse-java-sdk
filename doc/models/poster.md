
# Poster

## Structure

`Poster`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Extras` | `String` | Required | - | String getExtras() | setExtras(String extras) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `UserId` | `int` | Required | - | int getUserId() | setUserId(int userId) |
| `PrimaryGroupId` | `Integer` | Required | - | Integer getPrimaryGroupId() | setPrimaryGroupId(Integer primaryGroupId) |

## Example

```java
import com.example.discourse.models.Poster;

Poster poster = new Poster.Builder(
    "extras8",
    "description6",
    62,
    234
)
.build();
```

