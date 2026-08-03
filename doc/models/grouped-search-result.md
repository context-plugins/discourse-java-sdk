
# Grouped Search Result

## Structure

`GroupedSearchResult`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `MorePosts` | `String` | Required | - | String getMorePosts() | setMorePosts(String morePosts) |
| `MoreUsers` | `String` | Required | - | String getMoreUsers() | setMoreUsers(String moreUsers) |
| `MoreCategories` | `String` | Required | - | String getMoreCategories() | setMoreCategories(String moreCategories) |
| `Term` | `String` | Required | - | String getTerm() | setTerm(String term) |
| `SearchLogId` | `int` | Required | - | int getSearchLogId() | setSearchLogId(int searchLogId) |
| `MoreFullPageResults` | `String` | Required | - | String getMoreFullPageResults() | setMoreFullPageResults(String moreFullPageResults) |
| `CanCreateTopic` | `boolean` | Required | - | boolean getCanCreateTopic() | setCanCreateTopic(boolean canCreateTopic) |
| `Error` | `String` | Required | - | String getError() | setError(String error) |
| `Extra` | [`Extra`](../../doc/models/extra.md) | Optional | - | Extra getExtra() | setExtra(Extra extra) |
| `PostIds` | `List<Object>` | Required | - | List<Object> getPostIds() | setPostIds(List<Object> postIds) |
| `UserIds` | `List<Object>` | Required | - | List<Object> getUserIds() | setUserIds(List<Object> userIds) |
| `CategoryIds` | `List<Object>` | Required | - | List<Object> getCategoryIds() | setCategoryIds(List<Object> categoryIds) |
| `TagIds` | `List<Object>` | Required | - | List<Object> getTagIds() | setTagIds(List<Object> tagIds) |
| `GroupIds` | `List<Object>` | Required | - | List<Object> getGroupIds() | setGroupIds(List<Object> groupIds) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extra;
import com.example.discourse.models.GroupedSearchResult;
import java.io.IOException;
import java.util.Arrays;

GroupedSearchResult groupedSearchResult = new GroupedSearchResult.Builder(
    "more_posts4",
    "more_users8",
    "more_categories2",
    "term6",
    50,
    "more_full_page_results2",
    false,
    "error6",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.extra(new Extra.Builder()
        .categories("categories8")
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.build();
```

