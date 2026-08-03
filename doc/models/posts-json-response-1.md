
# Posts Json Response 1

## Structure

`PostsJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `Raw` | `String` | Optional | - | String getRaw() | setRaw(String raw) |
| `Cooked` | `String` | Required | - | String getCooked() | setCooked(String cooked) |
| `PostNumber` | `int` | Required | - | int getPostNumber() | setPostNumber(int postNumber) |
| `PostType` | `int` | Required | - | int getPostType() | setPostType(int postType) |
| `PostsCount` | `int` | Required | - | int getPostsCount() | setPostsCount(int postsCount) |
| `UpdatedAt` | `String` | Required | - | String getUpdatedAt() | setUpdatedAt(String updatedAt) |
| `ReplyCount` | `int` | Required | - | int getReplyCount() | setReplyCount(int replyCount) |
| `ReplyToPostNumber` | `String` | Required | - | String getReplyToPostNumber() | setReplyToPostNumber(String replyToPostNumber) |
| `QuoteCount` | `int` | Required | - | int getQuoteCount() | setQuoteCount(int quoteCount) |
| `IncomingLinkCount` | `int` | Required | - | int getIncomingLinkCount() | setIncomingLinkCount(int incomingLinkCount) |
| `Reads` | `int` | Required | - | int getReads() | setReads(int reads) |
| `ReadersCount` | `int` | Required | - | int getReadersCount() | setReadersCount(int readersCount) |
| `Score` | `double` | Required | - | double getScore() | setScore(double score) |
| `Yours` | `boolean` | Required | - | boolean getYours() | setYours(boolean yours) |
| `TopicId` | `int` | Required | - | int getTopicId() | setTopicId(int topicId) |
| `TopicSlug` | `String` | Required | - | String getTopicSlug() | setTopicSlug(String topicSlug) |
| `DisplayUsername` | `String` | Required | - | String getDisplayUsername() | setDisplayUsername(String displayUsername) |
| `PrimaryGroupName` | `String` | Required | - | String getPrimaryGroupName() | setPrimaryGroupName(String primaryGroupName) |
| `FlairName` | `String` | Required | - | String getFlairName() | setFlairName(String flairName) |
| `FlairUrl` | `String` | Required | - | String getFlairUrl() | setFlairUrl(String flairUrl) |
| `FlairBgColor` | `String` | Required | - | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `FlairColor` | `String` | Required | - | String getFlairColor() | setFlairColor(String flairColor) |
| `FlairGroupId` | `Integer` | Optional | - | Integer getFlairGroupId() | setFlairGroupId(Integer flairGroupId) |
| `BadgesGranted` | `List<Object>` | Optional | - | List<Object> getBadgesGranted() | setBadgesGranted(List<Object> badgesGranted) |
| `Version` | `int` | Required | - | int getVersion() | setVersion(int version) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `CanDelete` | `boolean` | Required | - | boolean getCanDelete() | setCanDelete(boolean canDelete) |
| `CanRecover` | `boolean` | Required | - | boolean getCanRecover() | setCanRecover(boolean canRecover) |
| `CanSeeHiddenPost` | `Boolean` | Optional | - | Boolean getCanSeeHiddenPost() | setCanSeeHiddenPost(Boolean canSeeHiddenPost) |
| `CanWiki` | `boolean` | Required | - | boolean getCanWiki() | setCanWiki(boolean canWiki) |
| `UserTitle` | `String` | Required | - | String getUserTitle() | setUserTitle(String userTitle) |
| `Bookmarked` | `boolean` | Required | - | boolean getBookmarked() | setBookmarked(boolean bookmarked) |
| `ActionsSummary` | [`List<ActionsSummary>`](../../doc/models/actions-summary.md) | Required | - | List<ActionsSummary> getActionsSummary() | setActionsSummary(List<ActionsSummary> actionsSummary) |
| `Moderator` | `boolean` | Required | - | boolean getModerator() | setModerator(boolean moderator) |
| `Admin` | `boolean` | Required | - | boolean getAdmin() | setAdmin(boolean admin) |
| `Staff` | `boolean` | Required | - | boolean getStaff() | setStaff(boolean staff) |
| `UserId` | `int` | Required | - | int getUserId() | setUserId(int userId) |
| `DraftSequence` | `int` | Required | - | int getDraftSequence() | setDraftSequence(int draftSequence) |
| `Hidden` | `boolean` | Required | - | boolean getHidden() | setHidden(boolean hidden) |
| `TrustLevel` | `int` | Required | - | int getTrustLevel() | setTrustLevel(int trustLevel) |
| `DeletedAt` | `String` | Required | - | String getDeletedAt() | setDeletedAt(String deletedAt) |
| `UserDeleted` | `boolean` | Required | - | boolean getUserDeleted() | setUserDeleted(boolean userDeleted) |
| `EditReason` | `String` | Required | - | String getEditReason() | setEditReason(String editReason) |
| `CanViewEditHistory` | `boolean` | Required | - | boolean getCanViewEditHistory() | setCanViewEditHistory(boolean canViewEditHistory) |
| `Wiki` | `boolean` | Required | - | boolean getWiki() | setWiki(boolean wiki) |
| `ReviewableId` | `Integer` | Required | - | Integer getReviewableId() | setReviewableId(Integer reviewableId) |
| `ReviewableScoreCount` | `int` | Required | - | int getReviewableScoreCount() | setReviewableScoreCount(int reviewableScoreCount) |
| `ReviewableScorePendingCount` | `int` | Required | - | int getReviewableScorePendingCount() | setReviewableScorePendingCount(int reviewableScorePendingCount) |
| `PostUrl` | `String` | Required | - | String getPostUrl() | setPostUrl(String postUrl) |
| `PostLocalizations` | `List<Object>` | Optional | - | List<Object> getPostLocalizations() | setPostLocalizations(List<Object> postLocalizations) |
| `MentionedUsers` | `List<Object>` | Optional | - | List<Object> getMentionedUsers() | setMentionedUsers(List<Object> mentionedUsers) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.PostsJsonResponse1;
import java.io.IOException;
import java.util.Arrays;

PostsJsonResponse1 postsJsonResponse1 = new PostsJsonResponse1.Builder(
    142,
    "name4",
    "username4",
    "avatar_template4",
    "created_at2",
    "cooked6",
    38,
    32,
    24,
    "updated_at0",
    232,
    "reply_to_post_number0",
    156,
    184,
    60,
    180,
    209.14D,
    false,
    80,
    "topic_slug4",
    "display_username4",
    "primary_group_name2",
    "flair_name8",
    "flair_url4",
    "flair_bg_color8",
    "flair_color8",
    114,
    false,
    false,
    false,
    false,
    "user_title8",
    false,
    Arrays.asList(
        new ActionsSummary.Builder(
            218,
            false
        )
        .build()
    ),
    false,
    false,
    false,
    238,
    28,
    false,
    126,
    "deleted_at2",
    false,
    "edit_reason2",
    false,
    false,
    216,
    118,
    112,
    "post_url6"
)
.raw("raw8")
.flairGroupId(192)
.badgesGranted(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.canSeeHiddenPost(false)
.postLocalizations(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.build();
```

