
# Groups by Id Json Response

## Structure

`GroupsByIdJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Group` | [`Group1`](../../doc/models/group-1.md) | Required | - | Group1 getGroup() | setGroup(Group1 group) |
| `Extras` | [`Extras`](../../doc/models/extras.md) | Required | - | Extras getExtras() | setExtras(Extras extras) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Extras;
import com.example.discourse.models.Group1;
import com.example.discourse.models.GroupsByIdJsonResponse;
import java.io.IOException;
import java.util.Arrays;

GroupsByIdJsonResponse groupsByIdJsonResponse = new GroupsByIdJsonResponse.Builder(
    new Group1.Builder(
        38,
        false,
        "name8",
        122,
        234,
        174,
        false,
        "title6",
        "grant_trust_level0",
        "incoming_email2",
        false,
        "flair_url8",
        "flair_bg_color2",
        "flair_color8",
        "bio_raw0",
        "bio_cooked6",
        "bio_excerpt2",
        false,
        false,
        false,
        "full_name4",
        254,
        "membership_request_template6",
        false,
        142,
        false,
        false,
        false,
        false,
        false,
        false,
        "automatic_membership_email_domains2",
        "smtp_server0",
        "smtp_port0",
        50,
        "email_username6",
        "email_password0",
        204,
        false,
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
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
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        )
    )
    .userCount(122)
    .canEditGroup(false)
    .smtpUpdatedAt("smtp_updated_at6")
    .smtpUpdatedBy(ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .smtpEnabled(false)
    .build(),
    new Extras.Builder(
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        )
    )
    .build()
)
.build();
```

