
# Topic 1

## Structure

`Topic1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `FancyTitle` | `String` | Required | - | String getFancyTitle() | setFancyTitle(String fancyTitle) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `PostsCount` | `int` | Required | - | int getPostsCount() | setPostsCount(int postsCount) |
| `ReplyCount` | `int` | Required | - | int getReplyCount() | setReplyCount(int replyCount) |
| `HighestPostNumber` | `int` | Required | - | int getHighestPostNumber() | setHighestPostNumber(int highestPostNumber) |
| `ImageUrl` | `String` | Required | - | String getImageUrl() | setImageUrl(String imageUrl) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `LastPostedAt` | `String` | Required | - | String getLastPostedAt() | setLastPostedAt(String lastPostedAt) |
| `Bumped` | `boolean` | Required | - | boolean getBumped() | setBumped(boolean bumped) |
| `BumpedAt` | `String` | Required | - | String getBumpedAt() | setBumpedAt(String bumpedAt) |
| `Archetype` | `String` | Required | - | String getArchetype() | setArchetype(String archetype) |
| `Unseen` | `boolean` | Required | - | boolean getUnseen() | setUnseen(boolean unseen) |
| `Pinned` | `boolean` | Required | - | boolean getPinned() | setPinned(boolean pinned) |
| `Unpinned` | `String` | Required | - | String getUnpinned() | setUnpinned(String unpinned) |
| `Excerpt` | `String` | Required | - | String getExcerpt() | setExcerpt(String excerpt) |
| `Visible` | `boolean` | Required | - | boolean getVisible() | setVisible(boolean visible) |
| `Closed` | `boolean` | Required | - | boolean getClosed() | setClosed(boolean closed) |
| `Archived` | `boolean` | Required | - | boolean getArchived() | setArchived(boolean archived) |
| `Bookmarked` | `String` | Required | - | String getBookmarked() | setBookmarked(String bookmarked) |
| `Liked` | `String` | Required | - | String getLiked() | setLiked(String liked) |
| `Views` | `int` | Required | - | int getViews() | setViews(int views) |
| `LikeCount` | `int` | Required | - | int getLikeCount() | setLikeCount(int likeCount) |
| `HasSummary` | `boolean` | Required | - | boolean getHasSummary() | setHasSummary(boolean hasSummary) |
| `LastPosterUsername` | `String` | Required | - | String getLastPosterUsername() | setLastPosterUsername(String lastPosterUsername) |
| `CategoryId` | `int` | Required | - | int getCategoryId() | setCategoryId(int categoryId) |
| `PinnedGlobally` | `boolean` | Required | - | boolean getPinnedGlobally() | setPinnedGlobally(boolean pinnedGlobally) |
| `FeaturedLink` | `String` | Required | - | String getFeaturedLink() | setFeaturedLink(String featuredLink) |
| `Posters` | [`List<Poster>`](../../doc/models/poster.md) | Required | - | List<Poster> getPosters() | setPosters(List<Poster> posters) |

## Example

```java
import com.example.discourse.models.Poster;
import com.example.discourse.models.Topic1;
import java.util.Arrays;

Topic1 topic1 = new Topic1.Builder(
    214,
    "title8",
    "fancy_title2",
    "slug6",
    96,
    48,
    192,
    "image_url8",
    "created_at0",
    "last_posted_at6",
    false,
    "bumped_at8",
    "archetype8",
    false,
    false,
    "unpinned4",
    "excerpt4",
    false,
    false,
    false,
    "bookmarked2",
    "liked6",
    232,
    212,
    false,
    "last_poster_username6",
    48,
    false,
    "featured_link8",
    Arrays.asList(
        new Poster.Builder(
            "extras2",
            "description8",
            60,
            232
        )
        .build()
    )
)
.build();
```

