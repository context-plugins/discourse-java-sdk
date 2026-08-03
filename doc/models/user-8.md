
# User 8

## Structure

`User8`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `LastPostedAt` | `String` | Required | - | String getLastPostedAt() | setLastPostedAt(String lastPostedAt) |
| `LastSeenAt` | `String` | Required | - | String getLastSeenAt() | setLastSeenAt(String lastSeenAt) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `Ignored` | `boolean` | Required | - | boolean getIgnored() | setIgnored(boolean ignored) |
| `Muted` | `boolean` | Required | - | boolean getMuted() | setMuted(boolean muted) |
| `CanIgnoreUser` | `boolean` | Required | - | boolean getCanIgnoreUser() | setCanIgnoreUser(boolean canIgnoreUser) |
| `CanIgnoreUsers` | `Boolean` | Optional | - | Boolean getCanIgnoreUsers() | setCanIgnoreUsers(Boolean canIgnoreUsers) |
| `CanMuteUser` | `boolean` | Required | - | boolean getCanMuteUser() | setCanMuteUser(boolean canMuteUser) |
| `CanMuteUsers` | `Boolean` | Optional | - | Boolean getCanMuteUsers() | setCanMuteUsers(Boolean canMuteUsers) |
| `CanSendPrivateMessages` | `boolean` | Required | - | boolean getCanSendPrivateMessages() | setCanSendPrivateMessages(boolean canSendPrivateMessages) |
| `CanSendPrivateMessageToUser` | `boolean` | Required | - | boolean getCanSendPrivateMessageToUser() | setCanSendPrivateMessageToUser(boolean canSendPrivateMessageToUser) |
| `TrustLevel` | `int` | Required | - | int getTrustLevel() | setTrustLevel(int trustLevel) |
| `Moderator` | `boolean` | Required | - | boolean getModerator() | setModerator(boolean moderator) |
| `Admin` | `boolean` | Required | - | boolean getAdmin() | setAdmin(boolean admin) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `BadgeCount` | `int` | Required | - | int getBadgeCount() | setBadgeCount(int badgeCount) |
| `SecondFactorBackupEnabled` | `Boolean` | Optional | - | Boolean getSecondFactorBackupEnabled() | setSecondFactorBackupEnabled(Boolean secondFactorBackupEnabled) |
| `UserFields` | `Map<String, String>` | Optional | - | Map<String, String> getUserFields() | setUserFields(Map<String, String> userFields) |
| `CustomFields` | [`CustomFields`](../../doc/models/custom-fields.md) | Required | - | CustomFields getCustomFields() | setCustomFields(CustomFields customFields) |
| `TimeRead` | `int` | Required | - | int getTimeRead() | setTimeRead(int timeRead) |
| `RecentTimeRead` | `int` | Required | - | int getRecentTimeRead() | setRecentTimeRead(int recentTimeRead) |
| `PrimaryGroupId` | `Integer` | Required | - | Integer getPrimaryGroupId() | setPrimaryGroupId(Integer primaryGroupId) |
| `PrimaryGroupName` | `String` | Required | - | String getPrimaryGroupName() | setPrimaryGroupName(String primaryGroupName) |
| `FlairGroupId` | `Integer` | Required | - | Integer getFlairGroupId() | setFlairGroupId(Integer flairGroupId) |
| `FlairName` | `String` | Required | - | String getFlairName() | setFlairName(String flairName) |
| `FlairUrl` | `String` | Required | - | String getFlairUrl() | setFlairUrl(String flairUrl) |
| `FlairBgColor` | `String` | Required | - | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `FlairColor` | `String` | Required | - | String getFlairColor() | setFlairColor(String flairColor) |
| `FeaturedTopic` | [`FeaturedTopic`](../../doc/models/featured-topic.md) | Required | - | FeaturedTopic getFeaturedTopic() | setFeaturedTopic(FeaturedTopic featuredTopic) |
| `Staged` | `boolean` | Required | - | boolean getStaged() | setStaged(boolean staged) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `CanEditUsername` | `boolean` | Required | - | boolean getCanEditUsername() | setCanEditUsername(boolean canEditUsername) |
| `CanEditEmail` | `boolean` | Required | - | boolean getCanEditEmail() | setCanEditEmail(boolean canEditEmail) |
| `CanEditName` | `boolean` | Required | - | boolean getCanEditName() | setCanEditName(boolean canEditName) |
| `UploadedAvatarId` | `Integer` | Required | - | Integer getUploadedAvatarId() | setUploadedAvatarId(Integer uploadedAvatarId) |
| `HasTitleBadges` | `boolean` | Required | - | boolean getHasTitleBadges() | setHasTitleBadges(boolean hasTitleBadges) |
| `PendingCount` | `int` | Required | - | int getPendingCount() | setPendingCount(int pendingCount) |
| `PendingPostsCount` | `Integer` | Optional | - | Integer getPendingPostsCount() | setPendingPostsCount(Integer pendingPostsCount) |
| `ProfileViewCount` | `int` | Required | - | int getProfileViewCount() | setProfileViewCount(int profileViewCount) |
| `SecondFactorEnabled` | `boolean` | Required | - | boolean getSecondFactorEnabled() | setSecondFactorEnabled(boolean secondFactorEnabled) |
| `CanUploadProfileHeader` | `boolean` | Required | - | boolean getCanUploadProfileHeader() | setCanUploadProfileHeader(boolean canUploadProfileHeader) |
| `CanUploadUserCardBackground` | `boolean` | Required | - | boolean getCanUploadUserCardBackground() | setCanUploadUserCardBackground(boolean canUploadUserCardBackground) |
| `PostCount` | `int` | Required | - | int getPostCount() | setPostCount(int postCount) |
| `TopicCount` | `int` | Required | - | int getTopicCount() | setTopicCount(int topicCount) |
| `CanBeDeleted` | `boolean` | Required | - | boolean getCanBeDeleted() | setCanBeDeleted(boolean canBeDeleted) |
| `CanDeleteAllPosts` | `boolean` | Required | - | boolean getCanDeleteAllPosts() | setCanDeleteAllPosts(boolean canDeleteAllPosts) |
| `Locale` | `String` | Required | - | String getLocale() | setLocale(String locale) |
| `MutedCategoryIds` | `List<Object>` | Required | - | List<Object> getMutedCategoryIds() | setMutedCategoryIds(List<Object> mutedCategoryIds) |
| `RegularCategoryIds` | `List<Object>` | Required | - | List<Object> getRegularCategoryIds() | setRegularCategoryIds(List<Object> regularCategoryIds) |
| `WatchedTags` | `List<Object>` | Required | - | List<Object> getWatchedTags() | setWatchedTags(List<Object> watchedTags) |
| `WatchingFirstPostTags` | `List<Object>` | Required | - | List<Object> getWatchingFirstPostTags() | setWatchingFirstPostTags(List<Object> watchingFirstPostTags) |
| `TrackedTags` | `List<Object>` | Required | - | List<Object> getTrackedTags() | setTrackedTags(List<Object> trackedTags) |
| `MutedTags` | `List<Object>` | Required | - | List<Object> getMutedTags() | setMutedTags(List<Object> mutedTags) |
| `TrackedCategoryIds` | `List<Object>` | Required | - | List<Object> getTrackedCategoryIds() | setTrackedCategoryIds(List<Object> trackedCategoryIds) |
| `WatchedCategoryIds` | `List<Object>` | Required | - | List<Object> getWatchedCategoryIds() | setWatchedCategoryIds(List<Object> watchedCategoryIds) |
| `WatchedFirstPostCategoryIds` | `List<Object>` | Required | - | List<Object> getWatchedFirstPostCategoryIds() | setWatchedFirstPostCategoryIds(List<Object> watchedFirstPostCategoryIds) |
| `SystemAvatarUploadId` | `String` | Required | - | String getSystemAvatarUploadId() | setSystemAvatarUploadId(String systemAvatarUploadId) |
| `SystemAvatarTemplate` | `String` | Required | - | String getSystemAvatarTemplate() | setSystemAvatarTemplate(String systemAvatarTemplate) |
| `MutedUsernames` | `List<Object>` | Required | - | List<Object> getMutedUsernames() | setMutedUsernames(List<Object> mutedUsernames) |
| `IgnoredUsernames` | `List<Object>` | Required | - | List<Object> getIgnoredUsernames() | setIgnoredUsernames(List<Object> ignoredUsernames) |
| `AllowedPmUsernames` | `List<Object>` | Required | - | List<Object> getAllowedPmUsernames() | setAllowedPmUsernames(List<Object> allowedPmUsernames) |
| `MailingListPostsPerDay` | `int` | Required | - | int getMailingListPostsPerDay() | setMailingListPostsPerDay(int mailingListPostsPerDay) |
| `CanChangeBio` | `boolean` | Required | - | boolean getCanChangeBio() | setCanChangeBio(boolean canChangeBio) |
| `CanChangeLocation` | `boolean` | Required | - | boolean getCanChangeLocation() | setCanChangeLocation(boolean canChangeLocation) |
| `CanChangeWebsite` | `boolean` | Required | - | boolean getCanChangeWebsite() | setCanChangeWebsite(boolean canChangeWebsite) |
| `CanChangeTrackingPreferences` | `boolean` | Required | - | boolean getCanChangeTrackingPreferences() | setCanChangeTrackingPreferences(boolean canChangeTrackingPreferences) |
| `UserApiKeys` | `String` | Required | - | String getUserApiKeys() | setUserApiKeys(String userApiKeys) |
| `UserPasskeys` | `List<Object>` | Optional | - | List<Object> getUserPasskeys() | setUserPasskeys(List<Object> userPasskeys) |
| `SidebarTags` | `List<Object>` | Optional | - | List<Object> getSidebarTags() | setSidebarTags(List<Object> sidebarTags) |
| `SidebarCategoryIds` | `List<Object>` | Optional | - | List<Object> getSidebarCategoryIds() | setSidebarCategoryIds(List<Object> sidebarCategoryIds) |
| `DisplaySidebarTags` | `Boolean` | Optional | - | Boolean getDisplaySidebarTags() | setDisplaySidebarTags(Boolean displaySidebarTags) |
| `CanPickThemeWithCustomHomepage` | `Boolean` | Optional | - | Boolean getCanPickThemeWithCustomHomepage() | setCanPickThemeWithCustomHomepage(Boolean canPickThemeWithCustomHomepage) |
| `UserAuthTokens` | [`List<UserAuthToken>`](../../doc/models/user-auth-token.md) | Required | - | List<UserAuthToken> getUserAuthTokens() | setUserAuthTokens(List<UserAuthToken> userAuthTokens) |
| `UserNotificationSchedule` | [`UserNotificationSchedule`](../../doc/models/user-notification-schedule.md) | Required | - | UserNotificationSchedule getUserNotificationSchedule() | setUserNotificationSchedule(UserNotificationSchedule userNotificationSchedule) |
| `UseLogoSmallAsAvatar` | `boolean` | Required | - | boolean getUseLogoSmallAsAvatar() | setUseLogoSmallAsAvatar(boolean useLogoSmallAsAvatar) |
| `FeaturedUserBadgeIds` | `List<Object>` | Required | - | List<Object> getFeaturedUserBadgeIds() | setFeaturedUserBadgeIds(List<Object> featuredUserBadgeIds) |
| `InvitedBy` | `String` | Required | - | String getInvitedBy() | setInvitedBy(String invitedBy) |
| `Groups` | [`List<Group7>`](../../doc/models/group-7.md) | Required | - | List<Group7> getGroups() | setGroups(List<Group7> groups) |
| `GroupUsers` | [`List<GroupUser>`](../../doc/models/group-user.md) | Required | - | List<GroupUser> getGroupUsers() | setGroupUsers(List<GroupUser> groupUsers) |
| `UserOption` | [`UserOption`](../../doc/models/user-option.md) | Required | - | UserOption getUserOption() | setUserOption(UserOption userOption) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.CustomFields;
import com.example.discourse.models.FeaturedTopic;
import com.example.discourse.models.Group7;
import com.example.discourse.models.GroupUser;
import com.example.discourse.models.User8;
import com.example.discourse.models.UserAuthToken;
import com.example.discourse.models.UserNotificationSchedule;
import com.example.discourse.models.UserOption;
import java.io.IOException;
import java.util.Arrays;
import java.util.LinkedHashMap;

User8 user8 = new User8.Builder(
    92,
    "username4",
    "name4",
    "avatar_template4",
    "last_posted_at4",
    "last_seen_at0",
    "created_at2",
    false,
    false,
    false,
    false,
    false,
    false,
    76,
    false,
    false,
    "title0",
    174,
    new CustomFields.Builder()
        .firstName("first_name2")
        .build(),
    40,
    186,
    104,
    "primary_group_name2",
    142,
    "flair_name8",
    "flair_url4",
    "flair_bg_color8",
    "flair_color8",
    new FeaturedTopic.Builder(
        50,
        "title6",
        "fancy_title0",
        "slug6",
        188
    )
    .build(),
    false,
    false,
    false,
    false,
    false,
    168,
    false,
    244,
    40,
    false,
    false,
    false,
    64,
    248,
    false,
    false,
    "locale2",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    "system_avatar_upload_id6",
    "system_avatar_template0",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    110,
    false,
    false,
    false,
    false,
    "user_api_keys0",
    Arrays.asList(
        new UserAuthToken.Builder(
            30,
            "client_ip2",
            "location6",
            "browser2",
            "device8",
            "os0",
            "icon4",
            "created_at0",
            "seen_at2",
            false
        )
        .build()
    ),
    new UserNotificationSchedule.Builder(
        false,
        242,
        54,
        130,
        246,
        112,
        212,
        160,
        110,
        186,
        212,
        48,
        64,
        102,
        208
    )
    .build(),
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    "invited_by8",
    Arrays.asList(
        new Group7.Builder(
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
        .build()
    ),
    Arrays.asList(
        new GroupUser.Builder(
            176,
            4,
            4
        )
        .owner(false)
        .build()
    ),
    new UserOption.Builder(
        122,
        false,
        176,
        false,
        112,
        58,
        false,
        "color_scheme_id2",
        "dark_scheme_id6",
        false,
        false,
        false,
        false,
        false,
        8,
        false,
        128,
        80,
        210,
        154,
        false,
        64,
        false,
        "push_notification_level4",
        false,
        false,
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        74,
        false,
        false,
        "homepage_id4",
        false,
        false,
        false,
        "text_size4",
        126,
        "title_count_mode4",
        "timezone2",
        false,
        false,
        78,
        false
    )
    .bookmarkAutoDeletePreference(190)
    .defaultCalendar("default_calendar2")
    .oldestSearchLogDate("oldest_search_log_date2")
    .sidebarLinkToFilteredList(false)
    .sidebarShowCountOfNewItems(false)
    .build()
)
.canIgnoreUsers(false)
.canMuteUsers(false)
.secondFactorBackupEnabled(false)
.userFields(new LinkedHashMap<String, String>() {{
        put("key0", "user_fields3");
        put("key1", "user_fields4");
        put("key2", "user_fields5");
    }})
.pendingPostsCount(108)
.build();
```

