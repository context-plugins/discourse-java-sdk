
# Groups Members Json Response

## Structure

`GroupsMembersJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Members` | [`List<Member>`](../../doc/models/member.md) | Required | - | List<Member> getMembers() | setMembers(List<Member> members) |
| `Owners` | [`List<Owner>`](../../doc/models/owner.md) | Required | - | List<Owner> getOwners() | setOwners(List<Owner> owners) |
| `Meta` | [`Meta`](../../doc/models/meta.md) | Required | - | Meta getMeta() | setMeta(Meta meta) |

## Example

```java
import com.example.discourse.models.GroupsMembersJsonResponse;
import com.example.discourse.models.Member;
import com.example.discourse.models.Meta;
import com.example.discourse.models.Owner;
import java.util.Arrays;

GroupsMembersJsonResponse groupsMembersJsonResponse = new GroupsMembersJsonResponse.Builder(
    Arrays.asList(
        new Member.Builder(
            204,
            "username2",
            "name8",
            "avatar_template2",
            "title6",
            "last_posted_at0",
            "last_seen_at4",
            "added_at6",
            "timezone2"
        )
        .build()
    ),
    Arrays.asList(
        new Owner.Builder(
            210,
            "username6",
            "name4",
            "avatar_template6",
            "title0",
            "last_posted_at4",
            "last_seen_at0",
            "added_at0",
            "timezone6"
        )
        .build()
    ),
    new Meta.Builder(
        36,
        126,
        222
    )
    .build()
)
.build();
```

