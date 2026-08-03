
# Post 2

## Structure

`Post2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
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
| `Raw` | `String` | Required | - | String getRaw() | setRaw(String raw) |
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
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `DisplayUsername` | `String` | Optional | - | String getDisplayUsername() | setDisplayUsername(String displayUsername) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.Post2;
import java.io.IOException;
import java.util.Arrays;

Post2 post2 = new Post2.Builder(
    92,
    "username0",
    "avatar_template0",
    "created_at8",
    "cooked2",
    244,
    238,
    230,
    "updated_at6",
    182,
    "reply_to_post_number6",
    106,
    234,
    10,
    130,
    211.2D,
    false,
    30,
    "topic_slug0",
    "primary_group_name8",
    "flair_name4",
    "flair_url0",
    "flair_bg_color4",
    "flair_color4",
    64,
    false,
    false,
    false,
    false,
    "user_title4",
    false,
    "raw4",
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
    188,
    234,
    false,
    76,
    "deleted_at8",
    false,
    "edit_reason8",
    false,
    false,
    166,
    68,
    162,
    "post_url2"
)
.flairGroupId(142)
.badgesGranted(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.canSeeHiddenPost(false)
.postLocalizations(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.mentionedUsers(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.build();
```

