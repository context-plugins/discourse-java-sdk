
# Topic List

## Structure

`TopicList`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CanCreateTopic` | `boolean` | Required | - | boolean getCanCreateTopic() | setCanCreateTopic(boolean canCreateTopic) |
| `PerPage` | `int` | Required | - | int getPerPage() | setPerPage(int perPage) |
| `TopTags` | [`List<TopTag>`](../../doc/models/top-tag.md) | Optional | - | List<TopTag> getTopTags() | setTopTags(List<TopTag> topTags) |
| `Topics` | [`List<Topic1>`](../../doc/models/topic-1.md) | Required | - | List<Topic1> getTopics() | setTopics(List<Topic1> topics) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Poster;
import com.example.discourse.models.TopTag;
import com.example.discourse.models.Topic1;
import com.example.discourse.models.TopicList;
import java.io.IOException;
import java.util.Arrays;

TopicList topicList = new TopicList.Builder(
    false,
    62,
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
        .build()
    ))
.build();
```

