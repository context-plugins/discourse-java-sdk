
# Suggested Topic

## Structure

`SuggestedTopic`

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
| `Tags` | [`List<Tag>`](../../doc/models/tag.md) | Required | - | List<Tag> getTags() | setTags(List<Tag> tags) |
| `TagsDescriptions` | `Object` | Required | - | Object getTagsDescriptions() | setTagsDescriptions(Object tagsDescriptions) |
| `LikeCount` | `int` | Required | - | int getLikeCount() | setLikeCount(int likeCount) |
| `Views` | `int` | Required | - | int getViews() | setViews(int views) |
| `CategoryId` | `int` | Required | - | int getCategoryId() | setCategoryId(int categoryId) |
| `FeaturedLink` | `String` | Required | - | String getFeaturedLink() | setFeaturedLink(String featuredLink) |
| `Posters` | [`List<Poster4>`](../../doc/models/poster-4.md) | Required | - | List<Poster4> getPosters() | setPosters(List<Poster4> posters) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Poster4;
import com.example.discourse.models.SuggestedTopic;
import com.example.discourse.models.Tag;
import com.example.discourse.models.User;
import java.io.IOException;
import java.util.Arrays;

SuggestedTopic suggestedTopic = new SuggestedTopic.Builder(
    68,
    "title4",
    "fancy_title8",
    "slug2",
    206,
    158,
    46,
    "image_url4",
    "created_at6",
    "last_posted_at0",
    false,
    "bumped_at4",
    "archetype4",
    false,
    false,
    "unpinned0",
    "excerpt0",
    false,
    false,
    false,
    "bookmarked8",
    "liked0",
    Arrays.asList(
        new Tag.Builder(
            26,
            "name0",
            "slug4"
        )
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build()
    ),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    66,
    122,
    194,
    "featured_link4",
    Arrays.asList(
        new Poster4.Builder(
            "extras2",
            "description8",
            new User.Builder(
                76,
                "username0",
                "name0",
                "avatar_template0"
            )
            .build()
        )
        .build()
    )
)
.build();
```

