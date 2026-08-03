
# Post 3

*This model accepts additional fields of type Object.*

## Structure

`Post3`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `Username` | `String` | Optional | - | String getUsername() | setUsername(String username) |
| `AvatarTemplate` | `String` | Optional | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `CreatedAt` | `String` | Optional | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `Cooked` | `String` | Optional | - | String getCooked() | setCooked(String cooked) |
| `PostNumber` | `Integer` | Optional | - | Integer getPostNumber() | setPostNumber(Integer postNumber) |
| `PostType` | `Integer` | Optional | - | Integer getPostType() | setPostType(Integer postType) |
| `UpdatedAt` | `String` | Optional | - | String getUpdatedAt() | setUpdatedAt(String updatedAt) |
| `ReplyCount` | `Integer` | Optional | - | Integer getReplyCount() | setReplyCount(Integer replyCount) |
| `ReplyToPostNumber` | `String` | Optional | - | String getReplyToPostNumber() | setReplyToPostNumber(String replyToPostNumber) |
| `QuoteCount` | `Integer` | Optional | - | Integer getQuoteCount() | setQuoteCount(Integer quoteCount) |
| `IncomingLinkCount` | `Integer` | Optional | - | Integer getIncomingLinkCount() | setIncomingLinkCount(Integer incomingLinkCount) |
| `Reads` | `Integer` | Optional | - | Integer getReads() | setReads(Integer reads) |
| `ReadersCount` | `Integer` | Optional | - | Integer getReadersCount() | setReadersCount(Integer readersCount) |
| `Score` | `Double` | Optional | - | Double getScore() | setScore(Double score) |
| `Yours` | `Boolean` | Optional | - | Boolean getYours() | setYours(Boolean yours) |
| `TopicId` | `Integer` | Optional | - | Integer getTopicId() | setTopicId(Integer topicId) |
| `TopicSlug` | `String` | Optional | - | String getTopicSlug() | setTopicSlug(String topicSlug) |
| `DisplayUsername` | `String` | Optional | - | String getDisplayUsername() | setDisplayUsername(String displayUsername) |
| `PrimaryGroupName` | `String` | Optional | - | String getPrimaryGroupName() | setPrimaryGroupName(String primaryGroupName) |
| `FlairName` | `String` | Optional | - | String getFlairName() | setFlairName(String flairName) |
| `FlairUrl` | `String` | Optional | - | String getFlairUrl() | setFlairUrl(String flairUrl) |
| `FlairBgColor` | `String` | Optional | - | String getFlairBgColor() | setFlairBgColor(String flairBgColor) |
| `FlairColor` | `String` | Optional | - | String getFlairColor() | setFlairColor(String flairColor) |
| `Version` | `Integer` | Optional | - | Integer getVersion() | setVersion(Integer version) |
| `CanEdit` | `Boolean` | Optional | - | Boolean getCanEdit() | setCanEdit(Boolean canEdit) |
| `CanDelete` | `Boolean` | Optional | - | Boolean getCanDelete() | setCanDelete(Boolean canDelete) |
| `CanRecover` | `Boolean` | Optional | - | Boolean getCanRecover() | setCanRecover(Boolean canRecover) |
| `CanWiki` | `Boolean` | Optional | - | Boolean getCanWiki() | setCanWiki(Boolean canWiki) |
| `Read` | `Boolean` | Optional | - | Boolean getRead() | setRead(Boolean read) |
| `UserTitle` | `String` | Optional | - | String getUserTitle() | setUserTitle(String userTitle) |
| `ActionsSummary` | [`List<ActionsSummary6>`](../../doc/models/actions-summary-6.md) | Optional | - | List<ActionsSummary6> getActionsSummary() | setActionsSummary(List<ActionsSummary6> actionsSummary) |
| `Moderator` | `Boolean` | Optional | - | Boolean getModerator() | setModerator(Boolean moderator) |
| `Admin` | `Boolean` | Optional | - | Boolean getAdmin() | setAdmin(Boolean admin) |
| `Staff` | `Boolean` | Optional | - | Boolean getStaff() | setStaff(Boolean staff) |
| `UserId` | `Integer` | Optional | - | Integer getUserId() | setUserId(Integer userId) |
| `Hidden` | `Boolean` | Optional | - | Boolean getHidden() | setHidden(Boolean hidden) |
| `TrustLevel` | `Integer` | Optional | - | Integer getTrustLevel() | setTrustLevel(Integer trustLevel) |
| `DeletedAt` | `String` | Optional | - | String getDeletedAt() | setDeletedAt(String deletedAt) |
| `UserDeleted` | `Boolean` | Optional | - | Boolean getUserDeleted() | setUserDeleted(Boolean userDeleted) |
| `EditReason` | `String` | Optional | - | String getEditReason() | setEditReason(String editReason) |
| `CanViewEditHistory` | `Boolean` | Optional | - | Boolean getCanViewEditHistory() | setCanViewEditHistory(Boolean canViewEditHistory) |
| `Wiki` | `Boolean` | Optional | - | Boolean getWiki() | setWiki(Boolean wiki) |
| `ReviewableId` | `Integer` | Optional | - | Integer getReviewableId() | setReviewableId(Integer reviewableId) |
| `ReviewableScoreCount` | `Integer` | Optional | - | Integer getReviewableScoreCount() | setReviewableScoreCount(Integer reviewableScoreCount) |
| `ReviewableScorePendingCount` | `Integer` | Optional | - | Integer getReviewableScorePendingCount() | setReviewableScorePendingCount(Integer reviewableScorePendingCount) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Post3;
import java.io.IOException;

Post3 post3 = new Post3.Builder()
    .id(168)
    .name("name8")
    .username("username8")
    .avatarTemplate("avatar_template8")
    .createdAt("created_at6")
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

