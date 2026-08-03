
# Posts Json Response 2

*This model accepts additional fields of type Object.*

## Structure

`PostsJsonResponse2`

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
| `Version` | `int` | Required | - | int getVersion() | setVersion(int version) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `CanDelete` | `boolean` | Required | - | boolean getCanDelete() | setCanDelete(boolean canDelete) |
| `CanRecover` | `boolean` | Required | - | boolean getCanRecover() | setCanRecover(boolean canRecover) |
| `CanSeeHiddenPost` | `Boolean` | Optional | - | Boolean getCanSeeHiddenPost() | setCanSeeHiddenPost(Boolean canSeeHiddenPost) |
| `CanWiki` | `boolean` | Required | - | boolean getCanWiki() | setCanWiki(boolean canWiki) |
| `UserTitle` | `String` | Required | - | String getUserTitle() | setUserTitle(String userTitle) |
| `Bookmarked` | `boolean` | Required | - | boolean getBookmarked() | setBookmarked(boolean bookmarked) |
| `Raw` | `String` | Required | - | String getRaw() | setRaw(String raw) |
| `ActionsSummary` | [`List<ActionsSummary2>`](../../doc/models/actions-summary-2.md) | Required | - | List<ActionsSummary2> getActionsSummary() | setActionsSummary(List<ActionsSummary2> actionsSummary) |
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
| `ReviewableId` | `Integer` | Required | - | Integer getReviewableId() | setReviewableId(Integer reviewableId) |
| `ReviewableScoreCount` | `int` | Required | - | int getReviewableScoreCount() | setReviewableScoreCount(int reviewableScoreCount) |
| `ReviewableScorePendingCount` | `int` | Required | - | int getReviewableScorePendingCount() | setReviewableScorePendingCount(int reviewableScorePendingCount) |
| `PostUrl` | `String` | Required | - | String getPostUrl() | setPostUrl(String postUrl) |
| `MentionedUsers` | `List<Object>` | Optional | - | List<Object> getMentionedUsers() | setMentionedUsers(List<Object> mentionedUsers) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `DisplayUsername` | `String` | Optional | - | String getDisplayUsername() | setDisplayUsername(String displayUsername) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary2;
import com.example.discourse.models.PostsJsonResponse2;
import java.io.IOException;
import java.util.Arrays;

PostsJsonResponse2 postsJsonResponse2 = new PostsJsonResponse2.Builder(
    184,
    "username4",
    "avatar_template6",
    "created_at2",
    "cooked4",
    80,
    74,
    66,
    "updated_at0",
    18,
    "reply_to_post_number0",
    198,
    142,
    102,
    222,
    63.64D,
    false,
    122,
    "topic_slug4",
    "primary_group_name2",
    "flair_name8",
    "flair_url4",
    "flair_bg_color8",
    "flair_color8",
    156,
    false,
    false,
    false,
    false,
    "user_title8",
    false,
    "raw8",
    Arrays.asList(
        new ActionsSummary2.Builder(
            218
        )
        .count(46)
        .acted(false)
        .canUndo(false)
        .canAct(false)
        .build()
    ),
    false,
    false,
    false,
    24,
    false,
    168,
    "deleted_at2",
    false,
    "edit_reason2",
    false,
    false,
    2,
    160,
    70,
    "post_url6"
)
.flairGroupId(234)
.canSeeHiddenPost(false)
.mentionedUsers(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.name("name4")
.displayUsername("display_username4")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

