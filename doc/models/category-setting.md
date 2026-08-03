
# Category Setting

## Structure

`CategorySetting`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `AutoBumpCooldownDays` | `Integer` | Optional | - | Integer getAutoBumpCooldownDays() | setAutoBumpCooldownDays(Integer autoBumpCooldownDays) |
| `NumAutoBumpDaily` | `Integer` | Optional | - | Integer getNumAutoBumpDaily() | setNumAutoBumpDaily(Integer numAutoBumpDaily) |
| `RequireReplyApproval` | `Boolean` | Optional | - | Boolean getRequireReplyApproval() | setRequireReplyApproval(Boolean requireReplyApproval) |
| `RequireTopicApproval` | `Boolean` | Optional | - | Boolean getRequireTopicApproval() | setRequireTopicApproval(Boolean requireTopicApproval) |
| `NestedRepliesDefault` | `Boolean` | Optional | - | Boolean getNestedRepliesDefault() | setNestedRepliesDefault(Boolean nestedRepliesDefault) |
| `TopicPostingReviewMode` | `String` | Optional | - | String getTopicPostingReviewMode() | setTopicPostingReviewMode(String topicPostingReviewMode) |
| `ReplyPostingReviewMode` | `String` | Optional | - | String getReplyPostingReviewMode() | setReplyPostingReviewMode(String replyPostingReviewMode) |

## Example

```java
import com.example.discourse.models.CategorySetting;

CategorySetting categorySetting = new CategorySetting.Builder()
    .autoBumpCooldownDays(102)
    .numAutoBumpDaily(6)
    .requireReplyApproval(false)
    .requireTopicApproval(false)
    .nestedRepliesDefault(false)
    .build();
```

