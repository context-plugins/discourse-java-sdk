
# C Json Response

## Structure

`CJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Users` | [`List<User>`](../../doc/models/user.md) | Optional | - | List<User> getUsers() | setUsers(List<User> users) |
| `PrimaryGroups` | `List<Object>` | Optional | - | List<Object> getPrimaryGroups() | setPrimaryGroups(List<Object> primaryGroups) |
| `TopicList` | [`TopicList`](../../doc/models/topic-list.md) | Required | - | TopicList getTopicList() | setTopicList(TopicList topicList) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.CJsonResponse;
import com.example.discourse.models.Poster;
import com.example.discourse.models.TopTag;
import com.example.discourse.models.Topic1;
import com.example.discourse.models.TopicList;
import com.example.discourse.models.User;
import java.io.IOException;
import java.util.Arrays;

CJsonResponse cJsonResponse = new CJsonResponse.Builder(
    new TopicList.Builder(
        false,
        116,
        Arrays.asList(
            new Topic1.Builder(
                54,
                "title8",
                "fancy_title6",
                "slug0",
                192,
                144,
                224,
                "image_url2",
                "created_at4",
                "last_posted_at2",
                false,
                "bumped_at2",
                "archetype8",
                false,
                false,
                "unpinned8",
                "excerpt8",
                false,
                false,
                false,
                "bookmarked6",
                "liked2",
                136,
                52,
                false,
                "last_poster_username2",
                208,
                false,
                "featured_link2",
                Arrays.asList(
                    new Poster.Builder(
                        "extras2",
                        "description8",
                        60,
                        232
                    )
                    .build()
                )
            )
            .build()
        )
    )
    .topTags(Arrays.asList(
            new TopTag.Builder(
                22,
                "name8",
                "slug2"
            )
            .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
            new TopTag.Builder(
                22,
                "name8",
                "slug2"
            )
            .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build(),
            new TopTag.Builder(
                22,
                "name8",
                "slug2"
            )
            .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
        ))
    .build()
)
.users(Arrays.asList(
        new User.Builder(
            58,
            "username4",
            "name6",
            "avatar_template4"
        )
        .build(),
        new User.Builder(
            58,
            "username4",
            "name6",
            "avatar_template4"
        )
        .build()
    ))
.primaryGroups(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.build();
```

