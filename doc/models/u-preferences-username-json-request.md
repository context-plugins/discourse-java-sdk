
# U Preferences Username Json Request

## Structure

`UPreferencesUsernameJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `NewUsername` | `String` | Required | - | String getNewUsername() | setNewUsername(String newUsername) |

## Example

```java
import com.example.discourse.models.UPreferencesUsernameJsonRequest;

UPreferencesUsernameJsonRequest uPreferencesUsernameJsonRequest = new UPreferencesUsernameJsonRequest.Builder(
    "new_username6"
)
.build();
```

