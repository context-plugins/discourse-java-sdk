
# Admin Users Json Request

## Structure

`AdminUsersJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `DeletePosts` | `Boolean` | Optional | - | Boolean getDeletePosts() | setDeletePosts(Boolean deletePosts) |
| `BlockEmail` | `Boolean` | Optional | - | Boolean getBlockEmail() | setBlockEmail(Boolean blockEmail) |
| `BlockUrls` | `Boolean` | Optional | - | Boolean getBlockUrls() | setBlockUrls(Boolean blockUrls) |
| `BlockIp` | `Boolean` | Optional | - | Boolean getBlockIp() | setBlockIp(Boolean blockIp) |

## Example

```java
import com.example.discourse.models.AdminUsersJsonRequest;

AdminUsersJsonRequest adminUsersJsonRequest = new AdminUsersJsonRequest.Builder()
    .deletePosts(false)
    .blockEmail(false)
    .blockUrls(false)
    .blockIp(false)
    .build();
```

