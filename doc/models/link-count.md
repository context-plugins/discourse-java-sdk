
# Link Count

## Structure

`LinkCount`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Url` | `String` | Required | - | String getUrl() | setUrl(String url) |
| `Internal` | `boolean` | Required | - | boolean getInternal() | setInternal(boolean internal) |
| `Reflection` | `boolean` | Required | - | boolean getReflection() | setReflection(boolean reflection) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `Clicks` | `int` | Required | - | int getClicks() | setClicks(int clicks) |

## Example

```java
import com.example.discourse.models.LinkCount;

LinkCount linkCount = new LinkCount.Builder(
    "url4",
    false,
    false,
    "title6",
    246
)
.build();
```

