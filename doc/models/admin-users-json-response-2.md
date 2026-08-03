
# Admin Users Json Response 2

*This model accepts additional fields of type Object.*

## Structure

`AdminUsersJsonResponse2`

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
import com.example.discourse.models.AdminUsersJsonResponse2;
import java.io.IOException;
import java.util.Arrays;

AdminUsersJsonResponse2 adminUsersJsonResponse2 = new AdminUsersJsonResponse2.Builder(
    48,
    "username2",
    "name2",
    "avatar_template2",
    false,
    false,
    false,
    "last_seen_at8",
    "last_emailed_at0",
    "created_at0",
    33.42D,
    202.44D,
    99.7D,
    32,
    "manual_locked_trust_level0",
    "title8",
    252,
    false,
    68,
    160,
    62,
    20
)
.email("email4")
.secondaryEmails(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

