
# Tag Json Response

*This model accepts additional fields of type Object.*

## Structure

`TagJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Users` | [`List<User2>`](../../doc/models/user-2.md) | Optional | - | List<User2> getUsers() | setUsers(List<User2> users) |
| `PrimaryGroups` | `List<Object>` | Optional | - | List<Object> getPrimaryGroups() | setPrimaryGroups(List<Object> primaryGroups) |
| `TopicList` | [`TopicList3`](../../doc/models/topic-list-3.md) | Optional | - | TopicList3 getTopicList() | setTopicList(TopicList3 topicList) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TagJsonResponse;
import com.example.discourse.models.TopicList3;
import com.example.discourse.models.User2;
import java.io.IOException;
import java.util.Arrays;

TagJsonResponse tagJsonResponse = new TagJsonResponse.Builder()
    .users(Arrays.asList(
        new User2.Builder()
            .id(58)
            .username("username4")
            .name("name6")
            .avatarTemplate("avatar_template4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
        new User2.Builder()
            .id(58)
            .username("username4")
            .name("name6")
            .avatarTemplate("avatar_template4")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
    ))
    .primaryGroups(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
    .topicList(new TopicList3.Builder()
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

