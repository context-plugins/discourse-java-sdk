
# User Avatar Refresh Gravatar Json Response

## Structure

`UserAvatarRefreshGravatarJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `GravatarUploadId` | `Integer` | Required | - | Integer getGravatarUploadId() | setGravatarUploadId(Integer gravatarUploadId) |
| `GravatarAvatarTemplate` | `String` | Required | - | String getGravatarAvatarTemplate() | setGravatarAvatarTemplate(String gravatarAvatarTemplate) |

## Example

```java
import com.example.discourse.models.UserAvatarRefreshGravatarJsonResponse;

UserAvatarRefreshGravatarJsonResponse userAvatarRefreshGravatarJsonResponse = new UserAvatarRefreshGravatarJsonResponse.Builder(
    194,
    "gravatar_avatar_template8"
)
.build();
```

