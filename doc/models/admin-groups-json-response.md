
# Admin Groups Json Response

## Structure

`AdminGroupsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `BasicGroup` | [`BasicGroup`](../../doc/models/basic-group.md) | Required | - | BasicGroup getBasicGroup() | setBasicGroup(BasicGroup basicGroup) |

## Example

```java
import com.example.discourse.models.AdminGroupsJsonResponse;
import com.example.discourse.models.BasicGroup;

AdminGroupsJsonResponse adminGroupsJsonResponse = new AdminGroupsJsonResponse.Builder(
    new BasicGroup.Builder(
        132,
        false,
        "name8",
        28,
        216,
        72,
        80,
        false,
        "title6",
        "grant_trust_level0",
        "incoming_email2",
        false,
        "flair_url8",
        "flair_bg_color2",
        "flair_color2",
        "bio_raw0",
        "bio_cooked6",
        "bio_excerpt2",
        false,
        false,
        false,
        "full_name4",
        92,
        "membership_request_template6",
        236,
        false,
        false,
        false
    )
    .canEditGroup(false)
    .build()
)
.build();
```

