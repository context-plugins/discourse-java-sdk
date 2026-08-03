
# Invites Json Response

## Structure

`InvitesJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `InviteKey` | `String` | Required | - | String getInviteKey() | setInviteKey(String inviteKey) |
| `Link` | `String` | Required | - | String getLink() | setLink(String link) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `Email` | `String` | Required | - | String getEmail() | setEmail(String email) |
| `Domain` | `String` | Required | - | String getDomain() | setDomain(String domain) |
| `Emailed` | `boolean` | Required | - | boolean getEmailed() | setEmailed(boolean emailed) |
| `CanDeleteInvite` | `boolean` | Required | - | boolean getCanDeleteInvite() | setCanDeleteInvite(boolean canDeleteInvite) |
| `CustomMessage` | `String` | Required | - | String getCustomMessage() | setCustomMessage(String customMessage) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `UpdatedAt` | `String` | Required | - | String getUpdatedAt() | setUpdatedAt(String updatedAt) |
| `ExpiresAt` | `String` | Required | - | String getExpiresAt() | setExpiresAt(String expiresAt) |
| `Expired` | `boolean` | Required | - | boolean getExpired() | setExpired(boolean expired) |
| `GrantsAdmin` | `boolean` | Required | - | boolean getGrantsAdmin() | setGrantsAdmin(boolean grantsAdmin) |
| `GrantsModerator` | `boolean` | Required | - | boolean getGrantsModerator() | setGrantsModerator(boolean grantsModerator) |
| `Topics` | `List<Object>` | Required | - | List<Object> getTopics() | setTopics(List<Object> topics) |
| `Groups` | `List<Object>` | Required | - | List<Object> getGroups() | setGroups(List<Object> groups) |

## Example

```java
import com.example.discourse.models.InvitesJsonResponse;
import java.util.Arrays;

InvitesJsonResponse invitesJsonResponse = new InvitesJsonResponse.Builder(
    42,
    "invite_key6",
    "http://example.com/invites/9045fd767efe201ca60c6658bcf14158",
    "description6",
    "not-a-user-yet@example.com",
    "domain0",
    false,
    false,
    "Hello world!",
    "2021-01-01T12:00:00.000Z",
    "2021-01-01T12:00:00.000Z",
    "2021-02-01T12:00:00.000Z",
    false,
    false,
    false,
    Arrays.asList(

    ),
    Arrays.asList(

    )
)
.build();
```

