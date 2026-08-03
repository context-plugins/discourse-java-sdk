
# User Option

## Structure

`UserOption`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UserId` | `int` | Required | - | int getUserId() | setUserId(int userId) |
| `MailingListMode` | `boolean` | Required | - | boolean getMailingListMode() | setMailingListMode(boolean mailingListMode) |
| `MailingListModeFrequency` | `int` | Required | - | int getMailingListModeFrequency() | setMailingListModeFrequency(int mailingListModeFrequency) |
| `EmailDigests` | `boolean` | Required | - | boolean getEmailDigests() | setEmailDigests(boolean emailDigests) |
| `EmailLevel` | `int` | Required | - | int getEmailLevel() | setEmailLevel(int emailLevel) |
| `EmailMessagesLevel` | `int` | Required | - | int getEmailMessagesLevel() | setEmailMessagesLevel(int emailMessagesLevel) |
| `ExternalLinksInNewTab` | `boolean` | Required | - | boolean getExternalLinksInNewTab() | setExternalLinksInNewTab(boolean externalLinksInNewTab) |
| `BookmarkAutoDeletePreference` | `Integer` | Optional | - | Integer getBookmarkAutoDeletePreference() | setBookmarkAutoDeletePreference(Integer bookmarkAutoDeletePreference) |
| `ColorSchemeId` | `String` | Required | - | String getColorSchemeId() | setColorSchemeId(String colorSchemeId) |
| `DarkSchemeId` | `String` | Required | - | String getDarkSchemeId() | setDarkSchemeId(String darkSchemeId) |
| `DynamicFavicon` | `boolean` | Required | - | boolean getDynamicFavicon() | setDynamicFavicon(boolean dynamicFavicon) |
| `EnableQuoting` | `boolean` | Required | - | boolean getEnableQuoting() | setEnableQuoting(boolean enableQuoting) |
| `EnableSmartLists` | `boolean` | Required | - | boolean getEnableSmartLists() | setEnableSmartLists(boolean enableSmartLists) |
| `EnableMarkdownMonospaceFont` | `boolean` | Required | - | boolean getEnableMarkdownMonospaceFont() | setEnableMarkdownMonospaceFont(boolean enableMarkdownMonospaceFont) |
| `EnableDefer` | `boolean` | Required | - | boolean getEnableDefer() | setEnableDefer(boolean enableDefer) |
| `DigestAfterMinutes` | `int` | Required | - | int getDigestAfterMinutes() | setDigestAfterMinutes(int digestAfterMinutes) |
| `AutomaticallyUnpinTopics` | `boolean` | Required | - | boolean getAutomaticallyUnpinTopics() | setAutomaticallyUnpinTopics(boolean automaticallyUnpinTopics) |
| `AutoTrackTopicsAfterMsecs` | `int` | Required | - | int getAutoTrackTopicsAfterMsecs() | setAutoTrackTopicsAfterMsecs(int autoTrackTopicsAfterMsecs) |
| `NotificationLevelWhenReplying` | `int` | Required | - | int getNotificationLevelWhenReplying() | setNotificationLevelWhenReplying(int notificationLevelWhenReplying) |
| `NewTopicDurationMinutes` | `int` | Required | - | int getNewTopicDurationMinutes() | setNewTopicDurationMinutes(int newTopicDurationMinutes) |
| `EmailPreviousReplies` | `int` | Required | - | int getEmailPreviousReplies() | setEmailPreviousReplies(int emailPreviousReplies) |
| `EmailInReplyTo` | `boolean` | Required | - | boolean getEmailInReplyTo() | setEmailInReplyTo(boolean emailInReplyTo) |
| `LikeNotificationFrequency` | `int` | Required | - | int getLikeNotificationFrequency() | setLikeNotificationFrequency(int likeNotificationFrequency) |
| `NotifyOnLinkedPosts` | `boolean` | Required | - | boolean getNotifyOnLinkedPosts() | setNotifyOnLinkedPosts(boolean notifyOnLinkedPosts) |
| `PushNotificationLevel` | `String` | Required | - | String getPushNotificationLevel() | setPushNotificationLevel(String pushNotificationLevel) |
| `EnableUpcomingChangeAvailableNotifications` | `boolean` | Required | - | boolean getEnableUpcomingChangeAvailableNotifications() | setEnableUpcomingChangeAvailableNotifications(boolean enableUpcomingChangeAvailableNotifications) |
| `IncludeTl0InDigests` | `boolean` | Required | - | boolean getIncludeTl0InDigests() | setIncludeTl0InDigests(boolean includeTl0InDigests) |
| `ThemeIds` | `List<Object>` | Required | - | List<Object> getThemeIds() | setThemeIds(List<Object> themeIds) |
| `ThemeKeySeq` | `int` | Required | - | int getThemeKeySeq() | setThemeKeySeq(int themeKeySeq) |
| `AllowPrivateMessages` | `boolean` | Required | - | boolean getAllowPrivateMessages() | setAllowPrivateMessages(boolean allowPrivateMessages) |
| `EnableAllowedPmUsers` | `boolean` | Required | - | boolean getEnableAllowedPmUsers() | setEnableAllowedPmUsers(boolean enableAllowedPmUsers) |
| `HomepageId` | `String` | Required | - | String getHomepageId() | setHomepageId(String homepageId) |
| `HideProfileAndPresence` | `boolean` | Required | - | boolean getHideProfileAndPresence() | setHideProfileAndPresence(boolean hideProfileAndPresence) |
| `HideProfile` | `boolean` | Required | - | boolean getHideProfile() | setHideProfile(boolean hideProfile) |
| `HidePresence` | `boolean` | Required | - | boolean getHidePresence() | setHidePresence(boolean hidePresence) |
| `TextSize` | `String` | Required | - | String getTextSize() | setTextSize(String textSize) |
| `TextSizeSeq` | `int` | Required | - | int getTextSizeSeq() | setTextSizeSeq(int textSizeSeq) |
| `TitleCountMode` | `String` | Required | - | String getTitleCountMode() | setTitleCountMode(String titleCountMode) |
| `Timezone` | `String` | Required | - | String getTimezone() | setTimezone(String timezone) |
| `SkipNewUserTips` | `boolean` | Required | - | boolean getSkipNewUserTips() | setSkipNewUserTips(boolean skipNewUserTips) |
| `DefaultCalendar` | `String` | Optional | - | String getDefaultCalendar() | setDefaultCalendar(String defaultCalendar) |
| `OldestSearchLogDate` | `String` | Optional | - | String getOldestSearchLogDate() | setOldestSearchLogDate(String oldestSearchLogDate) |
| `SidebarLinkToFilteredList` | `Boolean` | Optional | - | Boolean getSidebarLinkToFilteredList() | setSidebarLinkToFilteredList(Boolean sidebarLinkToFilteredList) |
| `SidebarShowCountOfNewItems` | `Boolean` | Optional | - | Boolean getSidebarShowCountOfNewItems() | setSidebarShowCountOfNewItems(Boolean sidebarShowCountOfNewItems) |
| `WatchedPrecedenceOverMuted` | `Boolean` | Optional | - | Boolean getWatchedPrecedenceOverMuted() | setWatchedPrecedenceOverMuted(Boolean watchedPrecedenceOverMuted) |
| `SeenPopups` | `String` | Optional | - | String getSeenPopups() | setSeenPopups(String seenPopups) |
| `TopicsUnreadWhenClosed` | `boolean` | Required | - | boolean getTopicsUnreadWhenClosed() | setTopicsUnreadWhenClosed(boolean topicsUnreadWhenClosed) |
| `CompositionMode` | `Integer` | Optional | - | Integer getCompositionMode() | setCompositionMode(Integer compositionMode) |
| `InterfaceColorMode` | `int` | Required | - | int getInterfaceColorMode() | setInterfaceColorMode(int interfaceColorMode) |
| `ShowOriginalContent` | `boolean` | Required | - | boolean getShowOriginalContent() | setShowOriginalContent(boolean showOriginalContent) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UserOption;
import java.io.IOException;
import java.util.Arrays;

UserOption userOption = new UserOption.Builder(
    16,
    false,
    230,
    false,
    6,
    208,
    false,
    "color_scheme_id8",
    "dark_scheme_id6",
    false,
    false,
    false,
    false,
    false,
    142,
    false,
    22,
    230,
    104,
    252,
    false,
    214,
    false,
    "push_notification_level4",
    false,
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    180,
    false,
    false,
    "homepage_id6",
    false,
    false,
    false,
    "text_size6",
    20,
    "title_count_mode4",
    "timezone8",
    false,
    false,
    228,
    false
)
.bookmarkAutoDeletePreference(84)
.defaultCalendar("default_calendar2")
.oldestSearchLogDate("oldest_search_log_date2")
.sidebarLinkToFilteredList(false)
.sidebarShowCountOfNewItems(false)
.build();
```

