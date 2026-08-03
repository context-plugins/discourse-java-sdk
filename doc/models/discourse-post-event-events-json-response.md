
# Discourse Post Event Events Json Response

## Structure

`DiscoursePostEventEventsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Events` | [`List<Event>`](../../doc/models/event.md) | Required | - | List<Event> getEvents() | setEvents(List<Event> events) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.DateTimeHelper;
import com.example.discourse.models.DiscoursePostEventEventsJsonResponse;
import com.example.discourse.models.Event;
import com.example.discourse.models.Occurrence;
import com.example.discourse.models.Post;
import com.example.discourse.models.Status;
import com.example.discourse.models.Topic;
import java.io.IOException;
import java.util.Arrays;

DiscoursePostEventEventsJsonResponse discoursePostEventEventsJsonResponse = new DiscoursePostEventEventsJsonResponse.Builder(
    Arrays.asList(
        new Event.Builder(
            68,
            194,
            DateTimeHelper.fromRfc8601DateTime("2016-03-13T12:52:32.123Z"),
            DateTimeHelper.fromRfc8601DateTime("2016-03-13T12:52:32.123Z"),
            false,
            "timezone0",
            new Post.Builder(
                236,
                132,
                "url4",
                "category_slug4",
                new Topic.Builder(
                    54,
                    "title4",
                    Arrays.asList(
                        "tags3"
                    ),
                    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                    "slug2"
                )
                .build()
            )
            .build(),
            Arrays.asList(
                new Occurrence.Builder(
                    "starts_at4",
                    "ends_at0"
                )
                .build()
            ),
            false,
            false,
            false,
            false,
            false,
            false,
            false,
            false,
            false,
            Status.ENUM_PRIVATE,
            false
        )
        .name("name0")
        .recurrence("recurrence6")
        .recurrenceUntil(DateTimeHelper.fromRfc8601DateTime("2016-03-13T12:52:32.123Z"))
        .rrule("rrule0")
        .duration("duration6")
        .build()
    )
)
.build();
```

