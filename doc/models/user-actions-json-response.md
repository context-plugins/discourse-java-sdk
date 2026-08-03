
# User Actions Json Response

## Structure

`UserActionsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UserActions` | [`List<UserAction>`](../../doc/models/user-action.md) | Required | - | List<UserAction> getUserActions() | setUserActions(List<UserAction> userActions) |

## Example

```java
import com.example.discourse.models.UserAction;
import com.example.discourse.models.UserActionsJsonResponse;
import java.util.Arrays;

UserActionsJsonResponse userActionsJsonResponse = new UserActionsJsonResponse.Builder(
    Arrays.asList(
        new UserAction.Builder(
            "excerpt0",
            10,
            "created_at6",
            "avatar_template8",
            "acting_avatar_template0",
            "slug2",
            168,
            224,
            "target_name2",
            "target_username8",
            126,
            "post_id2",
            "username8",
            "name8",
            70,
            "acting_username2",
            "acting_name2",
            152,
            "title4",
            false,
            "hidden6",
            "post_type0",
            "action_code8",
            32,
            false,
            false
        )
        .build()
    )
)
.build();
```

