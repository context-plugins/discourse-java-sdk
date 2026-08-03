
# Post Actions Json Response

*This model accepts additional fields of type Object.*

## Structure

`PostActionsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | The ID of the post | int getId() | setId(int id) |
| `Name` | `String` | Required | The name of the post author | String getName() | setName(String name) |
| `Username` | `String` | Required | The username of the post author | String getUsername() | setUsername(String username) |
| `AvatarTemplate` | `String` | Required | Template for the author's avatar URL | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `CreatedAt` | `String` | Required | When the post was created | String getCreatedAt() | setCreatedAt(String createdAt) |
| `Cooked` | `String` | Required | The HTML content of the post | String getCooked() | setCooked(String cooked) |
| `PostNumber` | `int` | Required | The post number within the topic | int getPostNumber() | setPostNumber(int postNumber) |
| `PostType` | `int` | Required | The type of post | int getPostType() | setPostType(int postType) |
| `PostsCount` | `int` | Required | Total posts count for the user | int getPostsCount() | setPostsCount(int postsCount) |
| `UpdatedAt` | `String` | Required | When the post was last updated | String getUpdatedAt() | setUpdatedAt(String updatedAt) |
| `ReplyCount` | `int` | Required | Number of replies to this post | int getReplyCount() | setReplyCount(int replyCount) |
| `ReplyToPostNumber` | `String` | Required | Post number this post is replying to | String getReplyToPostNumber() | setReplyToPostNumber(String replyToPostNumber) |
| `QuoteCount` | `int` | Required | Number of times this post has been quoted | int getQuoteCount() | setQuoteCount(int quoteCount) |
| `IncomingLinkCount` | `int` | Required | Number of incoming links to this post | int getIncomingLinkCount() | setIncomingLinkCount(int incomingLinkCount) |
| `Reads` | `int` | Required | Number of reads | int getReads() | setReads(int reads) |
| `ReadersCount` | `int` | Required | Number of readers | int getReadersCount() | setReadersCount(int readersCount) |
| `Score` | `double` | Required | Post score | double getScore() | setScore(double score) |
| `Yours` | `boolean` | Required | Whether this post belongs to the current user | boolean getYours() | setYours(boolean yours) |
| `TopicId` | `int` | Required | ID of the topic this post belongs to | int getTopicId() | setTopicId(int topicId) |
| `TopicSlug` | `String` | Required | Slug of the topic this post belongs to | String getTopicSlug() | setTopicSlug(String topicSlug) |
| `DisplayUsername` | `String` | Required | Display username of the post author | String getDisplayUsername() | setDisplayUsername(String displayUsername) |
| `PrimaryGroupName` | `String` | Required | Primary group name of the author | String getPrimaryGroupName() | setPrimaryGroupName(String primaryGroupName) |
| `FlairName` | `String` | Required | Flair name of the author | String getFlairName() | setFlairName(String flairName) |
| `FlairUrl` | `String` | Required | Flair URL of the author | String getFlairUrl() | setFlairUrl(String flairUrl) |
| `FlairBgColor` | `String` | Required | Flair background color of the author | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `FlairColor` | `String` | Required | Flair color of the author | String getFlairColor() | setFlairColor(String flairColor) |
| `FlairGroupId` | `Integer` | Required | Flair group ID of the author | Integer getFlairGroupId() | setFlairGroupId(Integer flairGroupId) |
| `BadgesGranted` | `List<Object>` | Required | Badges granted to the user | List<Object> getBadgesGranted() | setBadgesGranted(List<Object> badgesGranted) |
| `Version` | `int` | Required | Version number of the post | int getVersion() | setVersion(int version) |
| `CanEdit` | `boolean` | Required | Whether the current user can edit this post | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `CanDelete` | `boolean` | Required | Whether the current user can delete this post | boolean getCanDelete() | setCanDelete(boolean canDelete) |
| `CanRecover` | `boolean` | Required | Whether the current user can recover this post | boolean getCanRecover() | setCanRecover(boolean canRecover) |
| `CanSeeHiddenPost` | `boolean` | Required | Whether the current user can see hidden posts | boolean getCanSeeHiddenPost() | setCanSeeHiddenPost(boolean canSeeHiddenPost) |
| `CanWiki` | `boolean` | Required | Whether the current user can wiki this post | boolean getCanWiki() | setCanWiki(boolean canWiki) |
| `UserTitle` | `String` | Required | Title of the post author | String getUserTitle() | setUserTitle(String userTitle) |
| `Bookmarked` | `boolean` | Required | Whether the post is bookmarked by the current user | boolean getBookmarked() | setBookmarked(boolean bookmarked) |
| `ActionsSummary` | [`List<ActionsSummary5>`](../../doc/models/actions-summary-5.md) | Required | Summary of actions performed on this post | List<ActionsSummary5> getActionsSummary() | setActionsSummary(List<ActionsSummary5> actionsSummary) |
| `Moderator` | `boolean` | Required | Whether the post author is a moderator | boolean getModerator() | setModerator(boolean moderator) |
| `Admin` | `boolean` | Required | Whether the post author is an admin | boolean getAdmin() | setAdmin(boolean admin) |
| `Staff` | `boolean` | Required | Whether the post author is staff | boolean getStaff() | setStaff(boolean staff) |
| `UserId` | `int` | Required | ID of the post author | int getUserId() | setUserId(int userId) |
| `Hidden` | `boolean` | Required | Whether the post is hidden | boolean getHidden() | setHidden(boolean hidden) |
| `TrustLevel` | `int` | Required | Trust level of the post author | int getTrustLevel() | setTrustLevel(int trustLevel) |
| `DeletedAt` | `String` | Required | When the post was deleted | String getDeletedAt() | setDeletedAt(String deletedAt) |
| `UserDeleted` | `boolean` | Required | Whether the post was deleted by the user | boolean getUserDeleted() | setUserDeleted(boolean userDeleted) |
| `EditReason` | `String` | Required | Reason for the last edit | String getEditReason() | setEditReason(String editReason) |
| `CanViewEditHistory` | `boolean` | Required | Whether the current user can view edit history | boolean getCanViewEditHistory() | setCanViewEditHistory(boolean canViewEditHistory) |
| `Wiki` | `boolean` | Required | Whether this is a wiki post | boolean getWiki() | setWiki(boolean wiki) |
| `ReviewableId` | `Integer` | Required | ID of the reviewable if this post is under review | Integer getReviewableId() | setReviewableId(Integer reviewableId) |
| `ReviewableScoreCount` | `int` | Required | Number of reviewable scores | int getReviewableScoreCount() | setReviewableScoreCount(int reviewableScoreCount) |
| `ReviewableScorePendingCount` | `int` | Required | Number of pending reviewable scores | int getReviewableScorePendingCount() | setReviewableScorePendingCount(int reviewableScorePendingCount) |
| `PostUrl` | `String` | Required | URL of the post | String getPostUrl() | setPostUrl(String postUrl) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary5;
import com.example.discourse.models.PostActionsJsonResponse;
import java.io.IOException;
import java.util.Arrays;

PostActionsJsonResponse postActionsJsonResponse = new PostActionsJsonResponse.Builder(
    0,
    "name2",
    "username2",
    "avatar_template8",
    "created_at0",
    "cooked6",
    152,
    110,
    138,
    "updated_at8",
    90,
    "reply_to_post_number8",
    14,
    70,
    174,
    38,
    2.92D,
    false,
    62,
    "topic_slug2",
    "display_username2",
    "primary_group_name0",
    "flair_name6",
    "flair_url2",
    "flair_bg_color6",
    "flair_color6",
    50,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    228,
    false,
    false,
    false,
    false,
    false,
    "user_title6",
    false,
    Arrays.asList(
        new ActionsSummary5.Builder()
            .id(218)
            .count(46)
            .acted(false)
            .canUndo(false)
            .canAct(false)
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
    ),
    false,
    false,
    false,
    96,
    false,
    240,
    "deleted_at0",
    false,
    "edit_reason0",
    false,
    false,
    74,
    232,
    254,
    "post_url4"
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

