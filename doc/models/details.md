
# Details

## Structure

`Details`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `NotificationLevel` | `int` | Required | - | int getNotificationLevel() | setNotificationLevel(int notificationLevel) |
| `CanMovePosts` | `boolean` | Required | - | boolean getCanMovePosts() | setCanMovePosts(boolean canMovePosts) |
| `CanDelete` | `boolean` | Required | - | boolean getCanDelete() | setCanDelete(boolean canDelete) |
| `CanRemoveAllowedUsers` | `boolean` | Required | - | boolean getCanRemoveAllowedUsers() | setCanRemoveAllowedUsers(boolean canRemoveAllowedUsers) |
| `CanCreatePost` | `boolean` | Required | - | boolean getCanCreatePost() | setCanCreatePost(boolean canCreatePost) |
| `CanReplyAsNewTopic` | `boolean` | Required | - | boolean getCanReplyAsNewTopic() | setCanReplyAsNewTopic(boolean canReplyAsNewTopic) |
| `CanInviteTo` | `Boolean` | Optional | - | Boolean getCanInviteTo() | setCanInviteTo(Boolean canInviteTo) |
| `CanInviteViaEmail` | `Boolean` | Optional | - | Boolean getCanInviteViaEmail() | setCanInviteViaEmail(Boolean canInviteViaEmail) |
| `CanFlagTopic` | `Boolean` | Optional | - | Boolean getCanFlagTopic() | setCanFlagTopic(Boolean canFlagTopic) |
| `CanConvertTopic` | `boolean` | Required | - | boolean getCanConvertTopic() | setCanConvertTopic(boolean canConvertTopic) |
| `CanReviewTopic` | `boolean` | Required | - | boolean getCanReviewTopic() | setCanReviewTopic(boolean canReviewTopic) |
| `CanCloseTopic` | `boolean` | Required | - | boolean getCanCloseTopic() | setCanCloseTopic(boolean canCloseTopic) |
| `CanArchiveTopic` | `boolean` | Required | - | boolean getCanArchiveTopic() | setCanArchiveTopic(boolean canArchiveTopic) |
| `CanSplitMergeTopic` | `boolean` | Required | - | boolean getCanSplitMergeTopic() | setCanSplitMergeTopic(boolean canSplitMergeTopic) |
| `CanEditStaffNotes` | `boolean` | Required | - | boolean getCanEditStaffNotes() | setCanEditStaffNotes(boolean canEditStaffNotes) |
| `CanToggleTopicVisibility` | `boolean` | Required | - | boolean getCanToggleTopicVisibility() | setCanToggleTopicVisibility(boolean canToggleTopicVisibility) |
| `CanPinUnpinTopic` | `boolean` | Required | - | boolean getCanPinUnpinTopic() | setCanPinUnpinTopic(boolean canPinUnpinTopic) |
| `CanBannerTopic` | `Boolean` | Optional | - | Boolean getCanBannerTopic() | setCanBannerTopic(Boolean canBannerTopic) |
| `CanModerateCategory` | `boolean` | Required | - | boolean getCanModerateCategory() | setCanModerateCategory(boolean canModerateCategory) |
| `CanRemoveSelfId` | `int` | Required | - | int getCanRemoveSelfId() | setCanRemoveSelfId(int canRemoveSelfId) |
| `Participants` | [`List<Participant1>`](../../doc/models/participant-1.md) | Optional | - | List<Participant1> getParticipants() | setParticipants(List<Participant1> participants) |
| `CreatedBy` | [`CreatedBy`](../../doc/models/created-by.md) | Required | - | CreatedBy getCreatedBy() | setCreatedBy(CreatedBy createdBy) |
| `LastPoster` | [`LastPoster`](../../doc/models/last-poster.md) | Required | - | LastPoster getLastPoster() | setLastPoster(LastPoster lastPoster) |

## Example

```java
import com.example.discourse.models.CreatedBy;
import com.example.discourse.models.Details;
import com.example.discourse.models.LastPoster;
import com.example.discourse.models.Participant1;
import java.util.Arrays;

Details details = new Details.Builder(
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
.build();
```

