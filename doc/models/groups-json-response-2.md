
# Groups Json Response 2

## Structure

`GroupsJsonResponse2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Groups` | [`List<Group4>`](../../doc/models/group-4.md) | Required | - | List<Group4> getGroups() | setGroups(List<Group4> groups) |
| `Extras` | [`Extras2`](../../doc/models/extras-2.md) | Required | - | Extras2 getExtras() | setExtras(Extras2 extras) |
| `TotalRowsGroups` | `int` | Required | - | int getTotalRowsGroups() | setTotalRowsGroups(int totalRowsGroups) |
| `LoadMoreGroups` | `String` | Required | - | String getLoadMoreGroups() | setLoadMoreGroups(String loadMoreGroups) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extras2;
import com.example.discourse.models.Group4;
import com.example.discourse.models.GroupsJsonResponse2;
import java.io.IOException;
import java.util.Arrays;

GroupsJsonResponse2 groupsJsonResponse2 = new GroupsJsonResponse2.Builder(
    Arrays.asList(
        new Group4.Builder(
            152,
            false,
            "name6",
            "display_name6",
            236,
            92,
            196,
            false,
            "title2",
            "grant_trust_level8",
            "incoming_email6",
            false,
            "flair_url6",
            "flair_bg_color0",
            "flair_color0",
            "bio_raw8",
            "bio_cooked2",
            "bio_excerpt0",
            false,
            false,
            false,
            "full_name2",
            112,
            "membership_request_template2",
            0,
            false,
            false,
            false
        )
        .userCount(248)
        .isGroupUser(false)
        .isGroupOwner(false)
        .canEditGroup(false)
        .build()
    ),
    new Extras2.Builder(
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        )
    )
    .build(),
    234,
    "load_more_groups6"
)
.build();
```

