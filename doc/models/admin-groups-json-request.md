
# Admin Groups Json Request

## Structure

`AdminGroupsJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Group` | [`Group`](../../doc/models/group.md) | Required | - | Group getGroup() | setGroup(Group group) |

## Example

```java
import com.example.discourse.models.AdminGroupsJsonRequest;
import com.example.discourse.models.Group;

AdminGroupsJsonRequest adminGroupsJsonRequest = new AdminGroupsJsonRequest.Builder(
    new Group.Builder(
        "name8"
    )
    .fullName("full_name4")
    .bioRaw("bio_raw0")
    .usernames("usernames0")
    .ownerUsernames("owner_usernames8")
    .automaticMembershipEmailDomains("automatic_membership_email_domains2")
    .build()
)
.build();
```

