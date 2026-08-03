
# T Json Response

## Structure

`TJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `PostStream` | [`PostStream1`](../../doc/models/post-stream-1.md) | Required | - | PostStream1 getPostStream() | setPostStream(PostStream1 postStream) |
| `TimelineLookup` | `List<Object>` | Required | - | List<Object> getTimelineLookup() | setTimelineLookup(List<Object> timelineLookup) |
| `SuggestedTopics` | [`List<SuggestedTopic>`](../../doc/models/suggested-topic.md) | Required | - | List<SuggestedTopic> getSuggestedTopics() | setSuggestedTopics(List<SuggestedTopic> suggestedTopics) |
| `Tags` | [`List<Tag>`](../../doc/models/tag.md) | Required | - | List<Tag> getTags() | setTags(List<Tag> tags) |
| `TagsDescriptions` | `Object` | Required | - | Object getTagsDescriptions() | setTagsDescriptions(Object tagsDescriptions) |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `FancyTitle` | `String` | Required | - | String getFancyTitle() | setFancyTitle(String fancyTitle) |
| `PostsCount` | `int` | Required | - | int getPostsCount() | setPostsCount(int postsCount) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `Views` | `int` | Required | - | int getViews() | setViews(int views) |
| `ReplyCount` | `int` | Required | - | int getReplyCount() | setReplyCount(int replyCount) |
| `LikeCount` | `int` | Required | - | int getLikeCount() | setLikeCount(int likeCount) |
| `LastPostedAt` | `String` | Required | - | String getLastPostedAt() | setLastPostedAt(String lastPostedAt) |
| `Visible` | `boolean` | Required | - | boolean getVisible() | setVisible(boolean visible) |
| `Closed` | `boolean` | Required | - | boolean getClosed() | setClosed(boolean closed) |
| `Archived` | `boolean` | Required | - | boolean getArchived() | setArchived(boolean archived) |
| `HasSummary` | `boolean` | Required | - | boolean getHasSummary() | setHasSummary(boolean hasSummary) |
| `Archetype` | `String` | Required | - | String getArchetype() | setArchetype(String archetype) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `CategoryId` | `int` | Required | - | int getCategoryId() | setCategoryId(int categoryId) |
| `WordCount` | `Integer` | Required | - | Integer getWordCount() | setWordCount(Integer wordCount) |
| `DeletedAt` | `String` | Required | - | String getDeletedAt() | setDeletedAt(String deletedAt) |
| `UserId` | `int` | Required | - | int getUserId() | setUserId(int userId) |
| `FeaturedLink` | `String` | Required | - | String getFeaturedLink() | setFeaturedLink(String featuredLink) |
| `PinnedGlobally` | `boolean` | Required | - | boolean getPinnedGlobally() | setPinnedGlobally(boolean pinnedGlobally) |
| `PinnedAt` | `String` | Required | - | String getPinnedAt() | setPinnedAt(String pinnedAt) |
| `PinnedUntil` | `String` | Required | - | String getPinnedUntil() | setPinnedUntil(String pinnedUntil) |
| `ImageUrl` | `String` | Required | - | String getImageUrl() | setImageUrl(String imageUrl) |
| `SlowModeSeconds` | `int` | Required | - | int getSlowModeSeconds() | setSlowModeSeconds(int slowModeSeconds) |
| `Draft` | `String` | Required | - | String getDraft() | setDraft(String draft) |
| `DraftKey` | `String` | Required | - | String getDraftKey() | setDraftKey(String draftKey) |
| `DraftSequence` | `int` | Required | - | int getDraftSequence() | setDraftSequence(int draftSequence) |
| `Unpinned` | `String` | Required | - | String getUnpinned() | setUnpinned(String unpinned) |
| `Pinned` | `boolean` | Required | - | boolean getPinned() | setPinned(boolean pinned) |
| `CurrentPostNumber` | `Integer` | Optional | - | Integer getCurrentPostNumber() | setCurrentPostNumber(Integer currentPostNumber) |
| `HighestPostNumber` | `Integer` | Required | - | Integer getHighestPostNumber() | setHighestPostNumber(Integer highestPostNumber) |
| `DeletedBy` | `String` | Required | - | String getDeletedBy() | setDeletedBy(String deletedBy) |
| `HasDeleted` | `boolean` | Required | - | boolean getHasDeleted() | setHasDeleted(boolean hasDeleted) |
| `ActionsSummary` | [`List<ActionsSummary8>`](../../doc/models/actions-summary-8.md) | Required | - | List<ActionsSummary8> getActionsSummary() | setActionsSummary(List<ActionsSummary8> actionsSummary) |
| `ChunkSize` | `int` | Required | - | int getChunkSize() | setChunkSize(int chunkSize) |
| `Bookmarked` | `boolean` | Required | - | boolean getBookmarked() | setBookmarked(boolean bookmarked) |
| `Bookmarks` | `List<Object>` | Required | - | List<Object> getBookmarks() | setBookmarks(List<Object> bookmarks) |
| `TopicTimer` | `String` | Required | - | String getTopicTimer() | setTopicTimer(String topicTimer) |
| `MessageBusLastId` | `int` | Required | - | int getMessageBusLastId() | setMessageBusLastId(int messageBusLastId) |
| `ParticipantCount` | `int` | Required | - | int getParticipantCount() | setParticipantCount(int participantCount) |
| `ShowReadIndicator` | `boolean` | Required | - | boolean getShowReadIndicator() | setShowReadIndicator(boolean showReadIndicator) |
| `Thumbnails` | `String` | Required | - | String getThumbnails() | setThumbnails(String thumbnails) |
| `SlowModeEnabledUntil` | `String` | Required | - | String getSlowModeEnabledUntil() | setSlowModeEnabledUntil(String slowModeEnabledUntil) |
| `Details` | [`Details`](../../doc/models/details.md) | Required | - | Details getDetails() | setDetails(Details details) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ActionsSummary;
import com.example.discourse.models.ActionsSummary8;
import com.example.discourse.models.CreatedBy;
import com.example.discourse.models.Details;
import com.example.discourse.models.LastPoster;
import com.example.discourse.models.LinkCount;
import com.example.discourse.models.Participant1;
import com.example.discourse.models.Post4;
import com.example.discourse.models.PostStream1;
import com.example.discourse.models.Poster4;
import com.example.discourse.models.SuggestedTopic;
import com.example.discourse.models.TJsonResponse;
import com.example.discourse.models.Tag;
import com.example.discourse.models.User;
import java.io.IOException;
import java.util.Arrays;

TJsonResponse tJsonResponse = new TJsonResponse.Builder(
    new PostStream1.Builder(
        Arrays.asList(
            new Post4.Builder(
                64,
                "name6",
                "username6",
                "avatar_template6",
                "created_at4",
                "cooked8",
                216,
                210,
                "updated_at2",
                154,
                "reply_to_post_number2",
                78,
                6,
                238,
                102,
                182.76D,
                false,
                2,
                "topic_slug6",
                "display_username6",
                "primary_group_name4",
                "flair_name0",
                "flair_url6",
                "flair_bg_color0",
                "flair_color0",
                36,
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
                "user_title0",
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
                160,
                false,
                48,
                "deleted_at4",
                false,
                "edit_reason4",
                false,
                false,
                138,
                40,
                190
            )
            .canSeeHiddenPost(false)
            .build()
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        )
    )
    .build(),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        new SuggestedTopic.Builder(
            132,
            "title4",
            "fancy_title8",
            "slug2",
            14,
            222,
            110,
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
            130,
            198,
            130,
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
        .build()
    ),
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
    0,
    "title2",
    "fancy_title2",
    138,
    "created_at0",
    190,
    90,
    254,
    "last_posted_at6",
    false,
    false,
    false,
    false,
    "archetype2",
    "slug4",
    6,
    160,
    "deleted_at0",
    96,
    "featured_link8",
    false,
    "pinned_at4",
    "pinned_until4",
    "image_url8",
    10,
    "draft4",
    "draft_key8",
    142,
    "unpinned4",
    false,
    22,
    "deleted_by8",
    false,
    Arrays.asList(
        new ActionsSummary8.Builder(
            218,
            46,
            false,
            false
        )
        .build()
    ),
    254,
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    "topic_timer2",
    178,
    188,
    false,
    "thumbnails2",
    "slow_mode_enabled_until4",
    new Details.Builder(
        false,
        30,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        false,
        168,
        new CreatedBy.Builder(
            188,
            "username8",
            "name2",
            "avatar_template8"
        )
        .build(),
        new LastPoster.Builder(
            254,
            "username2",
            "name8",
            "avatar_template2"
        )
        .build()
    )
    .canInviteTo(false)
    .canInviteViaEmail(false)
    .canFlagTopic(false)
    .canBannerTopic(false)
    .participants(Arrays.asList(
            new Participant1.Builder(
                34,
                "username4",
                "name4",
                "avatar_template6",
                6,
                "primary_group_name2",
                "flair_name8",
                "flair_url4",
                "flair_color8",
                "flair_bg_color8",
                false,
                false,
                18
            )
            .flairGroupId(84)
            .build(),
            new Participant1.Builder(
                34,
                "username4",
                "name4",
                "avatar_template6",
                6,
                "primary_group_name2",
                "flair_name8",
                "flair_url4",
                "flair_color8",
                "flair_bg_color8",
                false,
                false,
                18
            )
            .flairGroupId(84)
            .build(),
            new Participant1.Builder(
                34,
                "username4",
                "name4",
                "avatar_template6",
                6,
                "primary_group_name2",
                "flair_name8",
                "flair_url4",
                "flair_color8",
                "flair_bg_color8",
                false,
                false,
                18
            )
            .flairGroupId(84)
            .build()
        ))
    .build()
)
.currentPostNumber(188)
.build();
```

