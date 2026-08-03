
# Topics Private Messages Json Response

*This model accepts additional fields of type Object.*

## Structure

`TopicsPrivateMessagesJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Users` | [`List<User1>`](../../doc/models/user-1.md) | Optional | - | List<User1> getUsers() | setUsers(List<User1> users) |
| `PrimaryGroups` | `List<Object>` | Optional | - | List<Object> getPrimaryGroups() | setPrimaryGroups(List<Object> primaryGroups) |
| `TopicList` | [`TopicList1`](../../doc/models/topic-list-1.md) | Optional | - | TopicList1 getTopicList() | setTopicList(TopicList1 topicList) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TopicList1;
import com.example.discourse.models.TopicsPrivateMessagesJsonResponse;
import com.example.discourse.models.User1;
import java.io.IOException;
import java.util.Arrays;

TopicsPrivateMessagesJsonResponse topicsPrivateMessagesJsonResponse = new TopicsPrivateMessagesJsonResponse.Builder()
    .users(Arrays.asList(
        new User1.Builder()
            .id(58)
            .username("username4")
            .name("name6")
            .avatarTemplate("avatar_template4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
    ))
    .primaryGroups(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
    .topicList(new TopicList1.Builder()
        .canCreateTopic(false)
        .draft("draft6")
        .draftKey("draft_key4")
        .draftSequence(80)
        .perPage(116)
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

