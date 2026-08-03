
# Post 4

## Structure

`Post4`

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
| `Version` | `int` | Required | - | int getVersion() | setVersion(int version) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `CanDelete` | `boolean` | Required | - | boolean getCanDelete() | setCanDelete(boolean canDelete) |
| `CanRecover` | `boolean` | Required | - | boolean getCanRecover() | setCanRecover(boolean canRecover) |
| `CanSeeHiddenPost` | `Boolean` | Optional | - | Boolean getCanSeeHiddenPost() | setCanSeeHiddenPost(Boolean canSeeHiddenPost) |
| `CanWiki` | `boolean` | Required | - | boolean getCanWiki() | setCanWiki(boolean canWiki) |
| `LinkCounts` | [`List<LinkCount>`](../../doc/models/link-count.md) | Required | - | List<LinkCount> getLinkCounts() | setLinkCounts(List<LinkCount> linkCounts) |
| `Read` | `boolean` | Required | - | boolean getRead() | setRead(boolean read) |
| `UserTitle` | `String` | Required | - | String getUserTitle() | setUserTitle(String userTitle) |
| `Bookmarked` | `boolean` | Required | - | boolean getBookmarked() | setBookmarked(boolean bookmarked) |
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
| `ReviewableId` | `int` | Required | - | int getReviewableId() | setReviewableId(int reviewableId) |
| `ReviewableScoreCount` | `int` | Required | - | int getReviewableScoreCount() | setReviewableScoreCount(int reviewableScoreCount) |
| `ReviewableScorePendingCount` | `int` | Required | - | int getReviewableScorePendingCount() | setReviewableScorePendingCount(int reviewableScorePendingCount) |

## Example

```java
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.LinkCount;
import com.example.discourse.models.Post4;
import java.util.Arrays;

Post4 post4 = new Post4.Builder(
    118,
    "name2",
    "username2",
    "avatar_template8",
    "created_at0",
    "cooked6",
    14,
    248,
    "updated_at8",
    208,
    "reply_to_post_number8",
    132,
    208,
    220,
    156,
    252.42D,
    false,
    200,
    "topic_slug2",
    "display_username2",
    "primary_group_name0",
    "flair_name6",
    "flair_url2",
    "flair_bg_color6",
    "flair_color6",
    90,
    false,
    false,
    false,
    false,
    Arrays.asList(
        new LinkCount.Builder(
            "url4",
            false,
            false,
            "title6",
            220
        )
        .build()
    ),
    false,
    "user_title6",
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
    214,
    false,
    102,
    "deleted_at0",
    false,
    "edit_reason0",
    false,
    false,
    192,
    94,
    136
)
.canSeeHiddenPost(false)
.build();
```

