
# Parent Tag

## Structure

`ParentTag`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |

## Example

```java
import com.example.discourse.models.ParentTag;

ParentTag parentTag = new ParentTag.Builder(
    82,
    "name8",
    "slug8"
)
.build();
```

