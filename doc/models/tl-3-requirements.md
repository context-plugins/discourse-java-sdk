
# Tl 3 Requirements

## Structure

`Tl3Requirements`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `TimePeriod` | `int` | Required | - | int getTimePeriod() | setTimePeriod(int timePeriod) |
| `RequirementsMet` | `boolean` | Required | - | boolean getRequirementsMet() | setRequirementsMet(boolean requirementsMet) |
| `RequirementsLost` | `boolean` | Required | - | boolean getRequirementsLost() | setRequirementsLost(boolean requirementsLost) |
| `TrustLevelLocked` | `boolean` | Required | - | boolean getTrustLevelLocked() | setTrustLevelLocked(boolean trustLevelLocked) |
| `OnGracePeriod` | `boolean` | Required | - | boolean getOnGracePeriod() | setOnGracePeriod(boolean onGracePeriod) |
| `DaysVisited` | `int` | Required | - | int getDaysVisited() | setDaysVisited(int daysVisited) |
| `MinDaysVisited` | `int` | Required | - | int getMinDaysVisited() | setMinDaysVisited(int minDaysVisited) |
| `NumTopicsRepliedTo` | `int` | Required | - | int getNumTopicsRepliedTo() | setNumTopicsRepliedTo(int numTopicsRepliedTo) |
| `MinTopicsRepliedTo` | `int` | Required | - | int getMinTopicsRepliedTo() | setMinTopicsRepliedTo(int minTopicsRepliedTo) |
| `TopicsViewed` | `int` | Required | - | int getTopicsViewed() | setTopicsViewed(int topicsViewed) |
| `MinTopicsViewed` | `int` | Required | - | int getMinTopicsViewed() | setMinTopicsViewed(int minTopicsViewed) |
| `PostsRead` | `int` | Required | - | int getPostsRead() | setPostsRead(int postsRead) |
| `MinPostsRead` | `int` | Required | - | int getMinPostsRead() | setMinPostsRead(int minPostsRead) |
| `TopicsViewedAllTime` | `int` | Required | - | int getTopicsViewedAllTime() | setTopicsViewedAllTime(int topicsViewedAllTime) |
| `MinTopicsViewedAllTime` | `int` | Required | - | int getMinTopicsViewedAllTime() | setMinTopicsViewedAllTime(int minTopicsViewedAllTime) |
| `PostsReadAllTime` | `int` | Required | - | int getPostsReadAllTime() | setPostsReadAllTime(int postsReadAllTime) |
| `MinPostsReadAllTime` | `int` | Required | - | int getMinPostsReadAllTime() | setMinPostsReadAllTime(int minPostsReadAllTime) |
| `NumFlaggedPosts` | `int` | Required | - | int getNumFlaggedPosts() | setNumFlaggedPosts(int numFlaggedPosts) |
| `MaxFlaggedPosts` | `int` | Required | - | int getMaxFlaggedPosts() | setMaxFlaggedPosts(int maxFlaggedPosts) |
| `NumFlaggedByUsers` | `int` | Required | - | int getNumFlaggedByUsers() | setNumFlaggedByUsers(int numFlaggedByUsers) |
| `MaxFlaggedByUsers` | `int` | Required | - | int getMaxFlaggedByUsers() | setMaxFlaggedByUsers(int maxFlaggedByUsers) |
| `NumLikesGiven` | `int` | Required | - | int getNumLikesGiven() | setNumLikesGiven(int numLikesGiven) |
| `MinLikesGiven` | `int` | Required | - | int getMinLikesGiven() | setMinLikesGiven(int minLikesGiven) |
| `NumLikesReceived` | `int` | Required | - | int getNumLikesReceived() | setNumLikesReceived(int numLikesReceived) |
| `MinLikesReceived` | `int` | Required | - | int getMinLikesReceived() | setMinLikesReceived(int minLikesReceived) |
| `NumLikesReceivedDays` | `int` | Required | - | int getNumLikesReceivedDays() | setNumLikesReceivedDays(int numLikesReceivedDays) |
| `MinLikesReceivedDays` | `int` | Required | - | int getMinLikesReceivedDays() | setMinLikesReceivedDays(int minLikesReceivedDays) |
| `NumLikesReceivedUsers` | `int` | Required | - | int getNumLikesReceivedUsers() | setNumLikesReceivedUsers(int numLikesReceivedUsers) |
| `MinLikesReceivedUsers` | `int` | Required | - | int getMinLikesReceivedUsers() | setMinLikesReceivedUsers(int minLikesReceivedUsers) |
| `PenaltyCounts` | [`PenaltyCounts1`](../../doc/models/penalty-counts-1.md) | Required | - | PenaltyCounts1 getPenaltyCounts() | setPenaltyCounts(PenaltyCounts1 penaltyCounts) |

## Example

```java
import com.example.discourse.models.PenaltyCounts1;
import com.example.discourse.models.Tl3Requirements;

Tl3Requirements tl3Requirements = new Tl3Requirements.Builder(
    106,
    false,
    false,
    false,
    false,
    62,
    86,
    80,
    56,
    212,
    36,
    212,
    158,
    150,
    236,
    16,
    100,
    84,
    194,
    4,
    52,
    82,
    174,
    156,
    106,
    70,
    126,
    224,
    236,
    new PenaltyCounts1.Builder(
        44,
        238,
        2
    )
    .build()
)
.build();
```

