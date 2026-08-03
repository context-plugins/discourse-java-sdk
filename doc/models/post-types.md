
# Post Types

## Structure

`PostTypes`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Regular` | `int` | Required | - | int getRegular() | setRegular(int regular) |
| `ModeratorAction` | `int` | Required | - | int getModeratorAction() | setModeratorAction(int moderatorAction) |
| `SmallAction` | `int` | Required | - | int getSmallAction() | setSmallAction(int smallAction) |
| `Whisper` | `int` | Required | - | int getWhisper() | setWhisper(int whisper) |

## Example

```java
import com.example.discourse.models.PostTypes;

PostTypes postTypes = new PostTypes.Builder(
    210,
    166,
    122,
    188
)
.build();
```

