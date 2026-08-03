
# Notification Types

## Structure

`NotificationTypes`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Mentioned` | `int` | Required | - | int getMentioned() | setMentioned(int mentioned) |
| `Replied` | `int` | Required | - | int getReplied() | setReplied(int replied) |
| `Quoted` | `int` | Required | - | int getQuoted() | setQuoted(int quoted) |
| `Edited` | `int` | Required | - | int getEdited() | setEdited(int edited) |
| `Liked` | `int` | Required | - | int getLiked() | setLiked(int liked) |
| `PrivateMessage` | `int` | Required | - | int getPrivateMessage() | setPrivateMessage(int privateMessage) |
| `InvitedToPrivateMessage` | `int` | Required | - | int getInvitedToPrivateMessage() | setInvitedToPrivateMessage(int invitedToPrivateMessage) |
| `InviteeAccepted` | `int` | Required | - | int getInviteeAccepted() | setInviteeAccepted(int inviteeAccepted) |
| `Posted` | `int` | Required | - | int getPosted() | setPosted(int posted) |
| `WatchingCategoryOrTag` | `int` | Required | - | int getWatchingCategoryOrTag() | setWatchingCategoryOrTag(int watchingCategoryOrTag) |
| `NewFeatures` | `Integer` | Optional | - | Integer getNewFeatures() | setNewFeatures(Integer newFeatures) |
| `AdminProblems` | `Integer` | Optional | - | Integer getAdminProblems() | setAdminProblems(Integer adminProblems) |
| `MovedPost` | `int` | Required | - | int getMovedPost() | setMovedPost(int movedPost) |
| `Linked` | `int` | Required | - | int getLinked() | setLinked(int linked) |
| `GrantedBadge` | `int` | Required | - | int getGrantedBadge() | setGrantedBadge(int grantedBadge) |
| `InvitedToTopic` | `int` | Required | - | int getInvitedToTopic() | setInvitedToTopic(int invitedToTopic) |
| `Custom` | `int` | Required | - | int getCustom() | setCustom(int custom) |
| `GroupMentioned` | `int` | Required | - | int getGroupMentioned() | setGroupMentioned(int groupMentioned) |
| `GroupMessageSummary` | `int` | Required | - | int getGroupMessageSummary() | setGroupMessageSummary(int groupMessageSummary) |
| `WatchingFirstPost` | `int` | Required | - | int getWatchingFirstPost() | setWatchingFirstPost(int watchingFirstPost) |
| `TopicReminder` | `int` | Required | - | int getTopicReminder() | setTopicReminder(int topicReminder) |
| `LikedConsolidated` | `int` | Required | - | int getLikedConsolidated() | setLikedConsolidated(int likedConsolidated) |
| `LinkedConsolidated` | `int` | Required | - | int getLinkedConsolidated() | setLinkedConsolidated(int linkedConsolidated) |
| `PostApproved` | `int` | Required | - | int getPostApproved() | setPostApproved(int postApproved) |
| `CodeReviewCommitApproved` | `int` | Required | - | int getCodeReviewCommitApproved() | setCodeReviewCommitApproved(int codeReviewCommitApproved) |
| `MembershipRequestAccepted` | `int` | Required | - | int getMembershipRequestAccepted() | setMembershipRequestAccepted(int membershipRequestAccepted) |
| `MembershipRequestConsolidated` | `int` | Required | - | int getMembershipRequestConsolidated() | setMembershipRequestConsolidated(int membershipRequestConsolidated) |
| `BookmarkReminder` | `int` | Required | - | int getBookmarkReminder() | setBookmarkReminder(int bookmarkReminder) |
| `Reaction` | `int` | Required | - | int getReaction() | setReaction(int reaction) |
| `VotesReleased` | `int` | Required | - | int getVotesReleased() | setVotesReleased(int votesReleased) |
| `EventReminder` | `int` | Required | - | int getEventReminder() | setEventReminder(int eventReminder) |
| `EventInvitation` | `int` | Required | - | int getEventInvitation() | setEventInvitation(int eventInvitation) |
| `ChatMention` | `int` | Required | - | int getChatMention() | setChatMention(int chatMention) |
| `ChatMessage` | `int` | Required | - | int getChatMessage() | setChatMessage(int chatMessage) |
| `ChatInvitation` | `int` | Required | - | int getChatInvitation() | setChatInvitation(int chatInvitation) |
| `ChatGroupMention` | `int` | Required | - | int getChatGroupMention() | setChatGroupMention(int chatGroupMention) |
| `ChatQuoted` | `Integer` | Optional | - | Integer getChatQuoted() | setChatQuoted(Integer chatQuoted) |
| `ChatWatchedThread` | `Integer` | Optional | - | Integer getChatWatchedThread() | setChatWatchedThread(Integer chatWatchedThread) |
| `UpcomingChangeAvailable` | `Integer` | Optional | - | Integer getUpcomingChangeAvailable() | setUpcomingChangeAvailable(Integer upcomingChangeAvailable) |
| `UpcomingChangeAutomaticallyPromoted` | `Integer` | Optional | - | Integer getUpcomingChangeAutomaticallyPromoted() | setUpcomingChangeAutomaticallyPromoted(Integer upcomingChangeAutomaticallyPromoted) |
| `Assigned` | `Integer` | Optional | - | Integer getAssigned() | setAssigned(Integer assigned) |
| `QuestionAnswerUserCommented` | `Integer` | Optional | - | Integer getQuestionAnswerUserCommented() | setQuestionAnswerUserCommented(Integer questionAnswerUserCommented) |
| `Following` | `Integer` | Optional | - | Integer getFollowing() | setFollowing(Integer following) |
| `FollowingCreatedTopic` | `Integer` | Optional | - | Integer getFollowingCreatedTopic() | setFollowingCreatedTopic(Integer followingCreatedTopic) |
| `FollowingReplied` | `Integer` | Optional | - | Integer getFollowingReplied() | setFollowingReplied(Integer followingReplied) |
| `CirclesActivity` | `Integer` | Optional | - | Integer getCirclesActivity() | setCirclesActivity(Integer circlesActivity) |
| `Boost` | `Integer` | Optional | - | Integer getBoost() | setBoost(Integer boost) |
| `SuggestedEditCreated` | `Integer` | Optional | - | Integer getSuggestedEditCreated() | setSuggestedEditCreated(Integer suggestedEditCreated) |
| `SuggestedEditAccepted` | `Integer` | Optional | - | Integer getSuggestedEditAccepted() | setSuggestedEditAccepted(Integer suggestedEditAccepted) |

## Example

```java
import com.example.discourse.models.NotificationTypes;

NotificationTypes notificationTypes = new NotificationTypes.Builder(
    150,
    12,
    176,
    242,
    68,
    210,
    246,
    212,
    162,
    186,
    224,
    202,
    14,
    104,
    56,
    230,
    88,
    68,
    32,
    50,
    66,
    104,
    70,
    106,
    198,
    134,
    226,
    246,
    198,
    46,
    70,
    212,
    234,
    222
)
.newFeatures(116)
.adminProblems(100)
.chatQuoted(156)
.chatWatchedThread(214)
.upcomingChangeAvailable(230)
.build();
```

