
# Meta 1

## Structure

`Meta1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `LastUpdatedAt` | `String` | Required | - | String getLastUpdatedAt() | setLastUpdatedAt(String lastUpdatedAt) |
| `TotalRowsDirectoryItems` | `int` | Required | - | int getTotalRowsDirectoryItems() | setTotalRowsDirectoryItems(int totalRowsDirectoryItems) |
| `LoadMoreDirectoryItems` | `String` | Required | - | String getLoadMoreDirectoryItems() | setLoadMoreDirectoryItems(String loadMoreDirectoryItems) |

## Example

```java
import com.example.discourse.models.Meta1;

Meta1 meta1 = new Meta1.Builder(
    "last_updated_at6",
    242,
    "load_more_directory_items0"
)
.build();
```

