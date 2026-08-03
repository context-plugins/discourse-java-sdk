
# Admin Users List Json Response

*This model accepts additional fields of type Object.*

## Structure

`AdminUsersListJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `Email` | `String` | Optional | - | String getEmail() | setEmail(String email) |
| `SecondaryEmails` | `List<Object>` | Optional | - | List<Object> getSecondaryEmails() | setSecondaryEmails(List<Object> secondaryEmails) |
| `Active` | `boolean` | Required | - | boolean getActive() | setActive(boolean active) |
| `Admin` | `boolean` | Required | - | boolean getAdmin() | setAdmin(boolean admin) |
| `Moderator` | `boolean` | Required | - | boolean getModerator() | setModerator(boolean moderator) |
| `LastSeenAt` | `String` | Required | - | String getLastSeenAt() | setLastSeenAt(String lastSeenAt) |
| `LastEmailedAt` | `String` | Required | - | String getLastEmailedAt() | setLastEmailedAt(String lastEmailedAt) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `LastSeenAge` | `Double` | Required | - | Double getLastSeenAge() | setLastSeenAge(Double lastSeenAge) |
| `LastEmailedAge` | `Double` | Required | - | Double getLastEmailedAge() | setLastEmailedAge(Double lastEmailedAge) |
| `CreatedAtAge` | `Double` | Required | - | Double getCreatedAtAge() | setCreatedAtAge(Double createdAtAge) |
| `TrustLevel` | `int` | Required | - | int getTrustLevel() | setTrustLevel(int trustLevel) |
| `ManualLockedTrustLevel` | `String` | Required | - | String getManualLockedTrustLevel() | setManualLockedTrustLevel(String manualLockedTrustLevel) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `TimeRead` | `int` | Required | - | int getTimeRead() | setTimeRead(int timeRead) |
| `Staged` | `boolean` | Required | - | boolean getStaged() | setStaged(boolean staged) |
| `DaysVisited` | `int` | Required | - | int getDaysVisited() | setDaysVisited(int daysVisited) |
| `PostsReadCount` | `int` | Required | - | int getPostsReadCount() | setPostsReadCount(int postsReadCount) |
| `TopicsEntered` | `int` | Required | - | int getTopicsEntered() | setTopicsEntered(int topicsEntered) |
| `PostCount` | `int` | Required | - | int getPostCount() | setPostCount(int postCount) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.AdminUsersListJsonResponse;
import java.io.IOException;
import java.util.Arrays;

AdminUsersListJsonResponse adminUsersListJsonResponse = new AdminUsersListJsonResponse.Builder(
    208,
    "username0",
    "name0",
    "avatar_template0",
    false,
    false,
    false,
    "last_seen_at6",
    "last_emailed_at2",
    "created_at2",
    145.1D,
    58.12D,
    211.38D,
    64,
    "manual_locked_trust_level2",
    "title4",
    156,
    false,
    228,
    192,
    34,
    180
)
.email("email6")
.secondaryEmails(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

