
# Directory Items Json Response

## Structure

`DirectoryItemsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `DirectoryItems` | [`List<DirectoryItem>`](../../doc/models/directory-item.md) | Required | - | List<DirectoryItem> getDirectoryItems() | setDirectoryItems(List<DirectoryItem> directoryItems) |
| `Meta` | [`Meta1`](../../doc/models/meta-1.md) | Required | - | Meta1 getMeta() | setMeta(Meta1 meta) |

## Example

```java
import com.example.discourse.models.DirectoryItem;
import com.example.discourse.models.DirectoryItemsJsonResponse;
import com.example.discourse.models.Meta1;
import com.example.discourse.models.User11;
import java.util.Arrays;

DirectoryItemsJsonResponse directoryItemsJsonResponse = new DirectoryItemsJsonResponse.Builder(
    Arrays.asList(
        new DirectoryItem.Builder(
            130,
            168,
            52,
            144,
            30,
            102,
            132,
            150,
            new User11.Builder(
                76,
                "username0",
                "name0",
                "avatar_template0",
                "title4"
            )
            .build()
        )
        .build()
    ),
    new Meta1.Builder(
        "last_updated_at6",
        140,
        "load_more_directory_items0"
    )
    .build()
)
.build();
```

