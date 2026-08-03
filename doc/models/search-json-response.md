
# Search Json Response

## Structure

`SearchJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Posts` | `List<Object>` | Required | - | List<Object> getPosts() | setPosts(List<Object> posts) |
| `Users` | `List<Object>` | Required | - | List<Object> getUsers() | setUsers(List<Object> users) |
| `Categories` | `List<Object>` | Required | - | List<Object> getCategories() | setCategories(List<Object> categories) |
| `Tags` | [`List<Tag>`](../../doc/models/tag.md) | Required | - | List<Tag> getTags() | setTags(List<Tag> tags) |
| `Groups` | `List<Object>` | Required | - | List<Object> getGroups() | setGroups(List<Object> groups) |
| `GroupedSearchResult` | [`GroupedSearchResult`](../../doc/models/grouped-search-result.md) | Required | - | GroupedSearchResult getGroupedSearchResult() | setGroupedSearchResult(GroupedSearchResult groupedSearchResult) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extra;
import com.example.discourse.models.GroupedSearchResult;
import com.example.discourse.models.SearchJsonResponse;
import com.example.discourse.models.Tag;
import java.io.IOException;
import java.util.Arrays;

SearchJsonResponse searchJsonResponse = new SearchJsonResponse.Builder(
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        new Tag.Builder(
            26,
            "name0",
            "slug4"
        )
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build()
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    new GroupedSearchResult.Builder(
        "more_posts4",
        "more_users2",
        "more_categories2",
        "term6",
        80,
        "more_full_page_results2",
        false,
        "error6",
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        )
    )
    .extra(new Extra.Builder()
            .categories("categories8")
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build())
    .build()
)
.build();
```

