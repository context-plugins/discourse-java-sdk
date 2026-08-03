
# Directory Item

## Structure

`DirectoryItem`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `LikesReceived` | `int` | Required | - | int getLikesReceived() | setLikesReceived(int likesReceived) |
| `LikesGiven` | `int` | Required | - | int getLikesGiven() | setLikesGiven(int likesGiven) |
| `TopicsEntered` | `int` | Required | - | int getTopicsEntered() | setTopicsEntered(int topicsEntered) |
| `TopicCount` | `int` | Required | - | int getTopicCount() | setTopicCount(int topicCount) |
| `PostCount` | `int` | Required | - | int getPostCount() | setPostCount(int postCount) |
| `PostsRead` | `int` | Required | - | int getPostsRead() | setPostsRead(int postsRead) |
| `DaysVisited` | `int` | Required | - | int getDaysVisited() | setDaysVisited(int daysVisited) |
| `User` | [`User11`](../../doc/models/user-11.md) | Required | - | User11 getUser() | setUser(User11 user) |

## Example

```java
import com.example.discourse.models.DirectoryItem;
import com.example.discourse.models.User11;

DirectoryItem directoryItem = new DirectoryItem.Builder(
    30,
    68,
    208,
    44,
    186,
    2,
    32,
    50,
    new User11.Builder(
        76,
        "username0",
        "name0",
        "avatar_template0",
        "title4"
    )
    .build()
)
.build();
```

