
# Groups Members Json Response 1

## Structure

`GroupsMembersJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |
| `Usernames` | `List<Object>` | Required | - | List<Object> getUsernames() | setUsernames(List<Object> usernames) |
| `Emails` | `List<Object>` | Required | - | List<Object> getEmails() | setEmails(List<Object> emails) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.GroupsMembersJsonResponse1;
import java.io.IOException;
import java.util.Arrays;

GroupsMembersJsonResponse1 groupsMembersJsonResponse1 = new GroupsMembersJsonResponse1.Builder(
    "success2",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.build();
```

