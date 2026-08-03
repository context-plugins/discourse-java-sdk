
# Users Json Request

## Structure

`UsersJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Email` | `String` | Required | - | String getEmail() | setEmail(String email) |
| `Password` | `String` | Required | - | String getPassword() | setPassword(String password) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Active` | `Boolean` | Optional | This param requires an admin api key in the request<br>header or it will be ignored | Boolean getActive() | setActive(Boolean active) |
| `Approved` | `Boolean` | Optional | - | Boolean getApproved() | setApproved(Boolean approved) |
| `UserFields` | `Map<String, Boolean>` | Optional | - | Map<String, Boolean> getUserFields() | setUserFields(Map<String, Boolean> userFields) |
| `ExternalIds` | `Object` | Optional | - | Object getExternalIds() | setExternalIds(Object externalIds) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UsersJsonRequest;
import java.io.IOException;
import java.util.LinkedHashMap;

UsersJsonRequest usersJsonRequest = new UsersJsonRequest.Builder(
    "name6",
    "email0",
    "password0",
    "username4"
)
.active(false)
.approved(false)
.userFields(new LinkedHashMap<String, Boolean>() {{
        put("key0", true);
        put("key1", false);
    }})
.externalIds(ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

