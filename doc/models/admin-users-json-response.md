
# Admin Users Json Response

## Structure

`AdminUsersJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
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
| `AssociatedAccounts` | `List<Object>` | Optional | - | List<Object> getAssociatedAccounts() | setAssociatedAccounts(List<Object> associatedAccounts) |
| `CanSendActivationEmail` | `boolean` | Required | - | boolean getCanSendActivationEmail() | setCanSendActivationEmail(boolean canSendActivationEmail) |
| `CanActivate` | `boolean` | Required | - | boolean getCanActivate() | setCanActivate(boolean canActivate) |
| `CanDeactivate` | `boolean` | Required | - | boolean getCanDeactivate() | setCanDeactivate(boolean canDeactivate) |
| `CanChangeTrustLevel` | `Boolean` | Optional | - | Boolean getCanChangeTrustLevel() | setCanChangeTrustLevel(Boolean canChangeTrustLevel) |
| `IpAddress` | `String` | Required | - | String getIpAddress() | setIpAddress(String ipAddress) |
| `RegistrationIpAddress` | `String` | Required | - | String getRegistrationIpAddress() | setRegistrationIpAddress(String registrationIpAddress) |
| `CanGrantAdmin` | `boolean` | Required | - | boolean getCanGrantAdmin() | setCanGrantAdmin(boolean canGrantAdmin) |
| `CanRevokeAdmin` | `boolean` | Required | - | boolean getCanRevokeAdmin() | setCanRevokeAdmin(boolean canRevokeAdmin) |
| `CanGrantModeration` | `boolean` | Required | - | boolean getCanGrantModeration() | setCanGrantModeration(boolean canGrantModeration) |
| `CanRevokeModeration` | `boolean` | Required | - | boolean getCanRevokeModeration() | setCanRevokeModeration(boolean canRevokeModeration) |
| `CanImpersonate` | `boolean` | Required | - | boolean getCanImpersonate() | setCanImpersonate(boolean canImpersonate) |
| `LikeCount` | `int` | Required | - | int getLikeCount() | setLikeCount(int likeCount) |
| `LikeGivenCount` | `int` | Required | - | int getLikeGivenCount() | setLikeGivenCount(int likeGivenCount) |
| `TopicCount` | `int` | Required | - | int getTopicCount() | setTopicCount(int topicCount) |
| `FlagsGivenCount` | `int` | Required | - | int getFlagsGivenCount() | setFlagsGivenCount(int flagsGivenCount) |
| `FlagsReceivedCount` | `int` | Required | - | int getFlagsReceivedCount() | setFlagsReceivedCount(int flagsReceivedCount) |
| `PrivateTopicsCount` | `int` | Required | - | int getPrivateTopicsCount() | setPrivateTopicsCount(int privateTopicsCount) |
| `CanDeleteAllPosts` | `boolean` | Required | - | boolean getCanDeleteAllPosts() | setCanDeleteAllPosts(boolean canDeleteAllPosts) |
| `CanBeDeleted` | `Boolean` | Optional | - | Boolean getCanBeDeleted() | setCanBeDeleted(Boolean canBeDeleted) |
| `CanBeAnonymized` | `boolean` | Required | - | boolean getCanBeAnonymized() | setCanBeAnonymized(boolean canBeAnonymized) |
| `CanBeMerged` | `boolean` | Required | - | boolean getCanBeMerged() | setCanBeMerged(boolean canBeMerged) |
| `FullSuspendReason` | `String` | Required | - | String getFullSuspendReason() | setFullSuspendReason(String fullSuspendReason) |
| `LatestExport` | `Object` | Optional | - | Object getLatestExport() | setLatestExport(Object latestExport) |
| `FullSilenceReason` | `String` | Optional | - | String getFullSilenceReason() | setFullSilenceReason(String fullSilenceReason) |
| `SilenceReason` | `String` | Optional | - | String getSilenceReason() | setSilenceReason(String silenceReason) |
| `PostEditsCount` | `Integer` | Optional | - | Integer getPostEditsCount() | setPostEditsCount(Integer postEditsCount) |
| `PrimaryGroupId` | `Integer` | Required | - | Integer getPrimaryGroupId() | setPrimaryGroupId(Integer primaryGroupId) |
| `BadgeCount` | `int` | Required | - | int getBadgeCount() | setBadgeCount(int badgeCount) |
| `WarningsReceivedCount` | `int` | Required | - | int getWarningsReceivedCount() | setWarningsReceivedCount(int warningsReceivedCount) |
| `BounceScore` | `Integer` | Required | - | Integer getBounceScore() | setBounceScore(Integer bounceScore) |
| `ResetBounceScoreAfter` | `String` | Required | - | String getResetBounceScoreAfter() | setResetBounceScoreAfter(String resetBounceScoreAfter) |
| `CanViewActionLogs` | `boolean` | Required | - | boolean getCanViewActionLogs() | setCanViewActionLogs(boolean canViewActionLogs) |
| `CanDisableSecondFactor` | `boolean` | Required | - | boolean getCanDisableSecondFactor() | setCanDisableSecondFactor(boolean canDisableSecondFactor) |
| `CanDeleteSsoRecord` | `boolean` | Required | - | boolean getCanDeleteSsoRecord() | setCanDeleteSsoRecord(boolean canDeleteSsoRecord) |
| `ApiKeyCount` | `int` | Required | - | int getApiKeyCount() | setApiKeyCount(int apiKeyCount) |
| `SimilarUsersCount` | `Integer` | Optional | - | Integer getSimilarUsersCount() | setSimilarUsersCount(Integer similarUsersCount) |
| `SingleSignOnRecord` | `String` | Required | - | String getSingleSignOnRecord() | setSingleSignOnRecord(String singleSignOnRecord) |
| `ApprovedBy` | [`ApprovedBy`](../../doc/models/approved-by.md) | Required | - | ApprovedBy getApprovedBy() | setApprovedBy(ApprovedBy approvedBy) |
| `SuspendedBy` | `String` | Required | - | String getSuspendedBy() | setSuspendedBy(String suspendedBy) |
| `SilencedBy` | `String` | Required | - | String getSilencedBy() | setSilencedBy(String silencedBy) |
| `PenaltyCounts` | [`PenaltyCounts`](../../doc/models/penalty-counts.md) | Optional | - | PenaltyCounts getPenaltyCounts() | setPenaltyCounts(PenaltyCounts penaltyCounts) |
| `NextPenalty` | `String` | Optional | - | String getNextPenalty() | setNextPenalty(String nextPenalty) |
| `Tl3Requirements` | [`Tl3Requirements`](../../doc/models/tl-3-requirements.md) | Optional | - | Tl3Requirements getTl3Requirements() | setTl3Requirements(Tl3Requirements tl3Requirements) |
| `Groups` | [`List<Group10>`](../../doc/models/group-10.md) | Required | - | List<Group10> getGroups() | setGroups(List<Group10> groups) |
| `ExternalIds` | `Object` | Required | - | Object getExternalIds() | setExternalIds(Object externalIds) |
| `IncludeIp` | `boolean` | Required | - | boolean getIncludeIp() | setIncludeIp(boolean includeIp) |
| `UpcomingChangesStats` | [`List<UpcomingChangesStat>`](../../doc/models/upcoming-changes-stat.md) | Optional | - | List<UpcomingChangesStat> getUpcomingChangesStats() | setUpcomingChangesStats(List<UpcomingChangesStat> upcomingChangesStats) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.AdminUsersJsonResponse;
import com.example.discourse.models.ApprovedBy;
import com.example.discourse.models.Group10;
import java.io.IOException;
import java.util.Arrays;

AdminUsersJsonResponse adminUsersJsonResponse = new AdminUsersJsonResponse.Builder(
    194,
    "username4",
    "name4",
    "avatar_template6",
    false,
    false,
    false,
    "last_seen_at0",
    "last_emailed_at8",
    "created_at2",
    114.24D,
    27.26D,
    180.52D,
    178,
    "manual_locked_trust_level8",
    "title0",
    142,
    false,
    214,
    50,
    208,
    166,
    false,
    false,
    false,
    "ip_address4",
    "registration_ip_address0",
    false,
    false,
    false,
    false,
    false,
    192,
    210,
    94,
    34,
    188,
    2,
    false,
    false,
    false,
    "full_suspend_reason6",
    206,
    20,
    176,
    4,
    "reset_bounce_score_after8",
    false,
    false,
    false,
    228,
    "single_sign_on_record4",
    new ApprovedBy.Builder(
        188,
        "username6",
        "name4",
        "avatar_template6"
    )
    .build(),
    "suspended_by8",
    "silenced_by8",
    Arrays.asList(
        new Group10.Builder(
            152,
            false,
            "name6",
            "display_name6",
            248,
            236,
            92,
            196,
            false,
            "title2",
            "grant_trust_level8",
            "incoming_email6",
            false,
            "flair_url6",
            "flair_bg_color0",
            "flair_color0",
            "bio_raw8",
            "bio_cooked2",
            "bio_excerpt0",
            false,
            false,
            false,
            "full_name2",
            112,
            "membership_request_template2",
            0,
            false,
            false,
            false
        )
        .flairGroupId(202)
        .build()
    ),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    false
)
.associatedAccounts(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.canChangeTrustLevel(false)
.canBeDeleted(false)
.latestExport(ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.fullSilenceReason("full_silence_reason0")
.build();
```

