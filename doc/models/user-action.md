
# User Action

## Structure

`UserAction`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Excerpt` | `String` | Required | - | String getExcerpt() | setExcerpt(String excerpt) |
| `ActionType` | `int` | Required | - | int getActionType() | setActionType(int actionType) |
| `CreatedAt` | `String` | Required | - | String getCreatedAt() | setCreatedAt(String createdAt) |
| `AvatarTemplate` | `String` | Required | - | String getAvatarTemplate() | setAvatarTemplate(String avatarTemplate) |
| `ActingAvatarTemplate` | `String` | Required | - | String getActingAvatarTemplate() | setActingAvatarTemplate(String actingAvatarTemplate) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `TopicId` | `int` | Required | - | int getTopicId() | setTopicId(int topicId) |
| `TargetUserId` | `int` | Required | - | int getTargetUserId() | setTargetUserId(int targetUserId) |
| `TargetName` | `String` | Required | - | String getTargetName() | setTargetName(String targetName) |
| `TargetUsername` | `String` | Required | - | String getTargetUsername() | setTargetUsername(String targetUsername) |
| `PostNumber` | `int` | Required | - | int getPostNumber() | setPostNumber(int postNumber) |
| `PostId` | `String` | Required | - | String getPostId() | setPostId(String postId) |
| `Username` | `String` | Required | - | String getUsername() | setUsername(String username) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `UserId` | `int` | Required | - | int getUserId() | setUserId(int userId) |
| `ActingUsername` | `String` | Required | - | String getActingUsername() | setActingUsername(String actingUsername) |
| `ActingName` | `String` | Required | - | String getActingName() | setActingName(String actingName) |
| `ActingUserId` | `int` | Required | - | int getActingUserId() | setActingUserId(int actingUserId) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `Deleted` | `boolean` | Required | - | boolean getDeleted() | setDeleted(boolean deleted) |
| `Hidden` | `String` | Required | - | String getHidden() | setHidden(String hidden) |
| `PostType` | `String` | Required | - | String getPostType() | setPostType(String postType) |
| `ActionCode` | `String` | Required | - | String getActionCode() | setActionCode(String actionCode) |
| `CategoryId` | `int` | Required | - | int getCategoryId() | setCategoryId(int categoryId) |
| `Closed` | `boolean` | Required | - | boolean getClosed() | setClosed(boolean closed) |
| `Archived` | `boolean` | Required | - | boolean getArchived() | setArchived(boolean archived) |

## Example

```java
import com.example.discourse.models.UserAction;

UserAction userAction = new UserAction.Builder(
    "excerpt6",
    198,
    "created_at2",
    "avatar_template6",
    "acting_avatar_template6",
    "slug2",
    156,
    100,
    "target_name8",
    "target_username6",
    58,
    "post_id2",
    "username6",
    "name4",
    2,
    "acting_username2",
    "acting_name6",
    220,
    "title0",
    false,
    "hidden2",
    "post_type4",
    "action_code4",
    100,
    false,
    false
)
.build();
```

