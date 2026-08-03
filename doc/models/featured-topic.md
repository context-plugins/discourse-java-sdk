
# Featured Topic

## Structure

`FeaturedTopic`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `FancyTitle` | `String` | Required | - | String getFancyTitle() | setFancyTitle(String fancyTitle) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `PostsCount` | `int` | Required | - | int getPostsCount() | setPostsCount(int postsCount) |

## Example

```java
import com.example.discourse.models.FeaturedTopic;

FeaturedTopic featuredTopic = new FeaturedTopic.Builder(
    40,
    "title6",
    "fancy_title0",
    "slug4",
    178
)
.build();
```

