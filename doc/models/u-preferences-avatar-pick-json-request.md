
# U Preferences Avatar Pick Json Request

## Structure

`UPreferencesAvatarPickJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UploadId` | `int` | Required | - | int getUploadId() | setUploadId(int uploadId) |
| `Type` | [`Type1`](../../doc/models/type-1.md) | Required | - | Type1 getType() | setType(Type1 type) |

## Example

```java
import com.example.discourse.models.Type1;
import com.example.discourse.models.UPreferencesAvatarPickJsonRequest;

UPreferencesAvatarPickJsonRequest uPreferencesAvatarPickJsonRequest = new UPreferencesAvatarPickJsonRequest.Builder(
    94,
    Type1.GRAVATAR
)
.build();
```

