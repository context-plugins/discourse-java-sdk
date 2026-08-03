
# Topic 2

*This model accepts additional fields of type Object.*

## Structure

`Topic2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `Title` | `String` | Optional | - | String getTitle() | setTitle(String title) |
| `FancyTitle` | `String` | Optional | - | String getFancyTitle() | setFancyTitle(String fancyTitle) |
| `Slug` | `String` | Optional | - | String getSlug() | setSlug(String slug) |
| `PostsCount` | `Integer` | Optional | - | Integer getPostsCount() | setPostsCount(Integer postsCount) |
| `ReplyCount` | `Integer` | Optional | - | Integer getReplyCount() | setReplyCount(Integer replyCount) |
| `HighestPostNumber` | `Integer` | Optional | - | Integer getHighestPostNumber() | setHighestPostNumber(Integer highestPostNumber) |
| `ImageUrl` | `String` | Optional | - | String getImageUrl() | setImageUrl(String imageUrl) |
| `CreatedAt` | `String` | Optional | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `LastPostedAt` | `String` | Optional | - | String getLastPostedAt() | setLastPostedAt(String lastPostedAt) |
| `Bumped` | `Boolean` | Optional | - | Boolean getBumped() | setBumped(Boolean bumped) |
| `BumpedAt` | `String` | Optional | - | String getBumpedAt() | setBumpedAt(String bumpedAt) |
| `Archetype` | `String` | Optional | - | String getArchetype() | setArchetype(String archetype) |
| `Unseen` | `Boolean` | Optional | - | Boolean getUnseen() | setUnseen(Boolean unseen) |
| `LastReadPostNumber` | `Integer` | Optional | - | Integer getLastReadPostNumber() | setLastReadPostNumber(Integer lastReadPostNumber) |
| `UnreadPosts` | `Integer` | Optional | - | Integer getUnreadPosts() | setUnreadPosts(Integer unreadPosts) |
| `Pinned` | `Boolean` | Optional | - | Boolean getPinned() | setPinned(Boolean pinned) |
| `Unpinned` | `String` | Optional | - | String getUnpinned() | setUnpinned(String unpinned) |
| `Visible` | `Boolean` | Optional | - | Boolean getVisible() | setVisible(Boolean visible) |
| `Closed` | `Boolean` | Optional | - | Boolean getClosed() | setClosed(Boolean closed) |
| `Archived` | `Boolean` | Optional | - | Boolean getArchived() | setArchived(Boolean archived) |
| `NotificationLevel` | `Integer` | Optional | - | Integer getNotificationLevel() | setNotificationLevel(Integer notificationLevel) |
| `Bookmarked` | `Boolean` | Optional | - | Boolean getBookmarked() | setBookmarked(Boolean bookmarked) |
| `Liked` | `Boolean` | Optional | - | Boolean getLiked() | setLiked(Boolean liked) |
| `Views` | `Integer` | Optional | - | Integer getViews() | setViews(Integer views) |
| `LikeCount` | `Integer` | Optional | - | Integer getLikeCount() | setLikeCount(Integer likeCount) |
| `HasSummary` | `Boolean` | Optional | - | Boolean getHasSummary() | setHasSummary(Boolean hasSummary) |
| `LastPosterUsername` | `String` | Optional | - | String getLastPosterUsername() | setLastPosterUsername(String lastPosterUsername) |
| `CategoryId` | `String` | Optional | - | String getCategoryId() | setCategoryId(String categoryId) |
| `PinnedGlobally` | `Boolean` | Optional | - | Boolean getPinnedGlobally() | setPinnedGlobally(Boolean pinnedGlobally) |
| `FeaturedLink` | `String` | Optional | - | String getFeaturedLink() | setFeaturedLink(String featuredLink) |
| `AllowedUserCount` | `Integer` | Optional | - | Integer getAllowedUserCount() | setAllowedUserCount(Integer allowedUserCount) |
| `Posters` | [`List<Poster1>`](../../doc/models/poster-1.md) | Optional | - | List<Poster1> getPosters() | setPosters(List<Poster1> posters) |
| `Participants` | [`List<Participant>`](../../doc/models/participant.md) | Optional | - | List<Participant> getParticipants() | setParticipants(List<Participant> participants) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Topic2;
import java.io.IOException;

Topic2 topic2 = new Topic2.Builder()
    .id(240)
    .title("title6")
    .fancyTitle("fancy_title0")
    .slug("slug6")
    .postsCount(122)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

