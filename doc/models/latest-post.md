
# Latest Post

## Structure

`LatestPost`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
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
| `TopicTitle` | `String` | Required | - | String getTopicTitle() | setTopicTitle(String topicTitle) |
| `TopicHtmlTitle` | `String` | Required | - | String getTopicHtmlTitle() | setTopicHtmlTitle(String topicHtmlTitle) |
| `CategoryId` | `int` | Required | - | int getCategoryId() | setCategoryId(int categoryId) |
| `DisplayUsername` | `String` | Required | - | String getDisplayUsername() | setDisplayUsername(String displayUsername) |
| `PrimaryGroupName` | `String` | Required | - | String getPrimaryGroupName() | setPrimaryGroupName(String primaryGroupName) |
| `FlairName` | `String` | Required | - | String getFlairName() | setFlairName(String flairName) |
| `FlairUrl` | `String` | Required | - | String getFlairUrl() | setFlairUrl(String flairUrl) |
| `FlairBgColor` | `String` | Required | - | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `FlairColor` | `String` | Required | - | String getFlairColor() | setFlairColor(String flairColor) |
| `FlairGroupId` | `String` | Required | - | String getFlairGroupId() | setFlairGroupId(String flairGroupId) |
| `BadgesGranted` | `List<Object>` | Required | - | List<Object> getBadgesGranted() | setBadgesGranted(List<Object> badgesGranted) |
| `Version` | `int` | Required | - | int getVersion() | setVersion(int version) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `CanDelete` | `boolean` | Required | - | boolean getCanDelete() | setCanDelete(boolean canDelete) |
| `CanRecover` | `boolean` | Required | - | boolean getCanRecover() | setCanRecover(boolean canRecover) |
| `CanSeeHiddenPost` | `boolean` | Required | - | boolean getCanSeeHiddenPost() | setCanSeeHiddenPost(boolean canSeeHiddenPost) |
| `CanWiki` | `boolean` | Required | - | boolean getCanWiki() | setCanWiki(boolean canWiki) |
| `UserTitle` | `String` | Required | - | String getUserTitle() | setUserTitle(String userTitle) |
| `Bookmarked` | `boolean` | Required | - | boolean getBookmarked() | setBookmarked(boolean bookmarked) |
| `Raw` | `String` | Required | - | String getRaw() | setRaw(String raw) |
| `ActionsSummary` | [`List<ActionsSummary>`](../../doc/models/actions-summary.md) | Required | - | List<ActionsSummary> getActionsSummary() | setActionsSummary(List<ActionsSummary> actionsSummary) |
| `Moderator` | `boolean` | Required | - | boolean getModerator() | setModerator(boolean moderator) |
| `Admin` | `boolean` | Required | - | boolean getAdmin() | setAdmin(boolean admin) |
| `Staff` | `boolean` | Required | - | boolean getStaff() | setStaff(boolean staff) |
| `UserId` | `int` | Required | - | int getUserId() | setUserId(int userId) |
| `Hidden` | `boolean` | Required | - | boolean getHidden() | setHidden(boolean hidden) |
| `TrustLevel` | `int` | Required | - | int getTrustLevel() | setTrustLevel(int trustLevel) |
| `DeletedAt` | `String` | Required | - | String getDeletedAt() | setDeletedAt(String deletedAt) |
| `UserDeleted` | `boolean` | Required | - | boolean getUserDeleted() | setUserDeleted(boolean userDeleted) |
| `EditReason` | `String` | Required | - | String getEditReason() | setEditReason(String editReason) |
| `CanViewEditHistory` | `boolean` | Required | - | boolean getCanViewEditHistory() | setCanViewEditHistory(boolean canViewEditHistory) |
| `Wiki` | `boolean` | Required | - | boolean getWiki() | setWiki(boolean wiki) |
| `Excerpt` | `String` | Required | - | String getExcerpt() | setExcerpt(String excerpt) |
| `Truncated` | `boolean` | Required | - | boolean getTruncated() | setTruncated(boolean truncated) |
| `ReviewableId` | `String` | Required | - | String getReviewableId() | setReviewableId(String reviewableId) |
| `ReviewableScoreCount` | `int` | Required | - | int getReviewableScoreCount() | setReviewableScoreCount(int reviewableScoreCount) |
| `ReviewableScorePendingCount` | `int` | Required | - | int getReviewableScorePendingCount() | setReviewableScorePendingCount(int reviewableScorePendingCount) |
| `PostUrl` | `String` | Required | - | String getPostUrl() | setPostUrl(String postUrl) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.LatestPost;
import java.io.IOException;
import java.util.Arrays;

LatestPost latestPost = new LatestPost.Builder(
    74,
    "name4",
    "username4",
    "avatar_template6",
    "created_at2",
    "cooked4",
    226,
    36,
    212,
    "updated_at0",
    164,
    "reply_to_post_number0",
    88,
    252,
    248,
    112,
    36.94D,
    false,
    12,
    "topic_slug4",
    "topic_title0",
    "topic_html_title4",
    188,
    "display_username4",
    "primary_group_name2",
    "flair_name8",
    "flair_url4",
    "flair_bg_color8",
    "flair_color8",
    "flair_group_id2",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    46,
    false,
    false,
    false,
    false,
    false,
    "user_title8",
    false,
    "raw8",
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
    170,
    false,
    58,
    "deleted_at2",
    false,
    "edit_reason2",
    false,
    false,
    "excerpt6",
    false,
    "reviewable_id4",
    50,
    180,
    "post_url6"
)
.build();
```

