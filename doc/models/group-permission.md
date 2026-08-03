
# Group Permission

## Structure

`GroupPermission`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `PermissionType` | `int` | Required | - | int getPermissionType() | setPermissionType(int permissionType) |
| `GroupName` | `String` | Required | - | String getGroupName() | setGroupName(String groupName) |
| `GroupId` | `int` | Required | - | int getGroupId() | setGroupId(int groupId) |

## Example

```java
import com.example.discourse.models.GroupPermission;

GroupPermission groupPermission = new GroupPermission.Builder(
    202,
    "group_name8",
    174
)
.build();
```

