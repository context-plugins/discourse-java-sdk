
# User Auth Token

## Structure

`UserAuthToken`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `ClientIp` | `String` | Required | - | String getClientIp() | setClientIp(String clientIp) |
| `Location` | `String` | Required | - | String getLocation() | setLocation(String location) |
| `Browser` | `String` | Required | - | String getBrowser() | setBrowser(String browser) |
| `Device` | `String` | Required | - | String getDevice() | setDevice(String device) |
| `Os` | `String` | Required | - | String getOs() | setOs(String os) |
| `Icon` | `String` | Required | - | String getIcon() | setIcon(String icon) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `SeenAt` | `String` | Required | - | String getSeenAt() | setSeenAt(String seenAt) |
| `IsActive` | `boolean` | Required | - | boolean getIsActive() | setIsActive(boolean isActive) |

## Example

```java
import com.example.discourse.models.UserAuthToken;

UserAuthToken userAuthToken = new UserAuthToken.Builder(
    242,
    "client_ip4",
    "location8",
    "browser4",
    "device0",
    "os2",
    "icon6",
    "created_at2",
    "seen_at4",
    false
)
.build();
```

