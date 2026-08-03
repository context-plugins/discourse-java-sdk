
# Event

## Structure

`Event`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `CategoryId` | `Integer` | Required | - | Integer getCategoryId() | setCategoryId(Integer categoryId) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `Recurrence` | `String` | Optional | - | String getRecurrence() | setRecurrence(String recurrence) |
| `RecurrenceUntil` | `LocalDateTime` | Optional | - | LocalDateTime getRecurrenceUntil() | setRecurrenceUntil(LocalDateTime recurrenceUntil) |
| `StartsAt` | `LocalDateTime` | Required | - | LocalDateTime getStartsAt() | setStartsAt(LocalDateTime startsAt) |
| `EndsAt` | `LocalDateTime` | Required | - | LocalDateTime getEndsAt() | setEndsAt(LocalDateTime endsAt) |
| `Rrule` | `String` | Optional | - | String getRrule() | setRrule(String rrule) |
| `ShowLocalTime` | `boolean` | Required | - | boolean getShowLocalTime() | setShowLocalTime(boolean showLocalTime) |
| `Timezone` | `String` | Required | - | String getTimezone() | setTimezone(String timezone) |
| `Duration` | `String` | Optional | **Constraints**: *Pattern*: `^\d{2}:\d{2}:\d{2}$` | String getDuration() | setDuration(String duration) |
| `AllDay` | `Boolean` | Optional | - | Boolean getAllDay() | setAllDay(Boolean allDay) |
| `CustomFields` | `Object` | Optional | - | Object getCustomFields() | setCustomFields(Object customFields) |
| `Post` | [`Post`](../../doc/models/post.md) | Required | - | Post getPost() | setPost(Post post) |
| `Occurrences` | [`List<Occurrence>`](../../doc/models/occurrence.md) | Required | - | List<Occurrence> getOccurrences() | setOccurrences(List<Occurrence> occurrences) |
| `CanActOnDiscoursePostEvent` | `Boolean` | Required | - | Boolean getCanActOnDiscoursePostEvent() | setCanActOnDiscoursePostEvent(Boolean canActOnDiscoursePostEvent) |
| `CanUpdateAttendance` | `Boolean` | Required | - | Boolean getCanUpdateAttendance() | setCanUpdateAttendance(Boolean canUpdateAttendance) |
| `Creator` | [`Creator`](../../doc/models/creator.md) | Optional | - | Creator getCreator() | setCreator(Creator creator) |
| `IsClosed` | `boolean` | Required | - | boolean getIsClosed() | setIsClosed(boolean isClosed) |
| `IsExpired` | `boolean` | Required | - | boolean getIsExpired() | setIsExpired(boolean isExpired) |
| `IsOngoing` | `boolean` | Required | - | boolean getIsOngoing() | setIsOngoing(boolean isOngoing) |
| `IsPrivate` | `boolean` | Required | - | boolean getIsPrivate() | setIsPrivate(boolean isPrivate) |
| `IsPublic` | `boolean` | Required | - | boolean getIsPublic() | setIsPublic(boolean isPublic) |
| `IsStandalone` | `boolean` | Required | - | boolean getIsStandalone() | setIsStandalone(boolean isStandalone) |
| `Minimal` | `Boolean` | Optional | - | Boolean getMinimal() | setMinimal(Boolean minimal) |
| `RawInvitees` | `List<String>` | Optional | - | List<String> getRawInvitees() | setRawInvitees(List<String> rawInvitees) |
| `Reminders` | [`List<Reminder>`](../../doc/models/reminder.md) | Optional | - | List<Reminder> getReminders() | setReminders(List<Reminder> reminders) |
| `SampleInvitees` | `List<Object>` | Optional | - | List<Object> getSampleInvitees() | setSampleInvitees(List<Object> sampleInvitees) |
| `ShouldDisplayInvitees` | `boolean` | Required | - | boolean getShouldDisplayInvitees() | setShouldDisplayInvitees(boolean shouldDisplayInvitees) |
| `Stats` | `Object` | Optional | - | Object getStats() | setStats(Object stats) |
| `Status` | [`Status`](../../doc/models/status.md) | Required | - | Status getStatus() | setStatus(Status status) |
| `Url` | `String` | Optional | - | String getUrl() | setUrl(String url) |
| `Description` | `String` | Optional | - | String getDescription() | setDescription(String description) |
| `DescriptionHtml` | `String` | Optional | - | String getDescriptionHtml() | setDescriptionHtml(String descriptionHtml) |
| `Location` | `String` | Optional | - | String getLocation() | setLocation(String location) |
| `WatchingInvitee` | `Object` | Optional | - | Object getWatchingInvitee() | setWatchingInvitee(Object watchingInvitee) |
| `ChatEnabled` | `Boolean` | Optional | - | Boolean getChatEnabled() | setChatEnabled(Boolean chatEnabled) |
| `Channel` | `Object` | Optional | - | Object getChannel() | setChannel(Object channel) |
| `Livestream` | `Boolean` | Optional | - | Boolean getLivestream() | setLivestream(Boolean livestream) |
| `LivestreamOnebox` | `String` | Optional | - | String getLivestreamOnebox() | setLivestreamOnebox(String livestreamOnebox) |
| `IsZoomLivestream` | `Boolean` | Optional | - | Boolean getIsZoomLivestream() | setIsZoomLivestream(Boolean isZoomLivestream) |
| `MaxAttendees` | `Integer` | Optional | - | Integer getMaxAttendees() | setMaxAttendees(Integer maxAttendees) |
| `AtCapacity` | `boolean` | Required | - | boolean getAtCapacity() | setAtCapacity(boolean atCapacity) |
| `ImageUpload` | `Object` | Optional | - | Object getImageUpload() | setImageUpload(Object imageUpload) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.DateTimeHelper;
import com.example.discourse.models.Event;
import com.example.discourse.models.Occurrence;
import com.example.discourse.models.Post;
import com.example.discourse.models.Status;
import com.example.discourse.models.Topic;
import java.io.IOException;
import java.util.Arrays;

Event event = new Event.Builder(
    242,
    20,
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
    Status.STANDALONE,
    false
)
.name("name0")
.recurrence("recurrence6")
.recurrenceUntil(DateTimeHelper.fromRfc8601DateTime("2016-03-13T12:52:32.123Z"))
.rrule("rrule0")
.duration("duration6")
.build();
```

