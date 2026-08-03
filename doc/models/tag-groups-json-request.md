
# Tag Groups Json Request

## Structure

`TagGroupsJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |

## Example

```java
import com.example.discourse.models.TagGroupsJsonRequest;

TagGroupsJsonRequest tagGroupsJsonRequest = new TagGroupsJsonRequest.Builder(
    "name0"
)
.build();
```

