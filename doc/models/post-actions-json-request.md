
# Post Actions Json Request

## Structure

`PostActionsJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | The ID of the post to perform the action on | int getId() | setId(int id) |
| `PostActionTypeId` | `int` | Required | The ID of the post action type (e.g., 2 for like) | int getPostActionTypeId() | setPostActionTypeId(int postActionTypeId) |
| `FlagTopic` | `Boolean` | Optional | Whether to flag the entire topic | Boolean getFlagTopic() | setFlagTopic(Boolean flagTopic) |

## Example

```java
import com.example.discourse.models.PostActionsJsonRequest;

PostActionsJsonRequest postActionsJsonRequest = new PostActionsJsonRequest.Builder(
    78,
    76
)
.flagTopic(false)
.build();
```

