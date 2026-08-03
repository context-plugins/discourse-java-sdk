
# Top Json Response

*This model accepts additional fields of type Object.*

## Structure

`TopJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Users` | [`List<User1>`](../../doc/models/user-1.md) | Optional | - | List<User1> getUsers() | setUsers(List<User1> users) |
| `PrimaryGroups` | `List<Object>` | Optional | - | List<Object> getPrimaryGroups() | setPrimaryGroups(List<Object> primaryGroups) |
| `TopicList` | [`TopicList5`](../../doc/models/topic-list-5.md) | Optional | - | TopicList5 getTopicList() | setTopicList(TopicList5 topicList) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TopJsonResponse;
import com.example.discourse.models.TopicList5;
import com.example.discourse.models.User1;
import java.io.IOException;
import java.util.Arrays;

TopJsonResponse topJsonResponse = new TopJsonResponse.Builder()
    .users(Arrays.asList(
        new User1.Builder()
            .id(58)
            .username("username4")
            .name("name6")
            .avatarTemplate("avatar_template4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
        new User1.Builder()
            .id(58)
            .username("username4")
            .name("name6")
            .avatarTemplate("avatar_template4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
        new User1.Builder()
            .id(58)
            .username("username4")
            .name("name6")
            .avatarTemplate("avatar_template4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
    ))
    .primaryGroups(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
    .topicList(new TopicList5.Builder()
        .canCreateTopic(false)
        .draft("draft6")
        .draftKey("draft_key4")
        .draftSequence(80)
        .forPeriod("for_period6")
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

