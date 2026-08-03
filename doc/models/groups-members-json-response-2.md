
# Groups Members Json Response 2

## Structure

`GroupsMembersJsonResponse2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |
| `Usernames` | `List<Object>` | Required | - | List<Object> getUsernames() | setUsernames(List<Object> usernames) |
| `SkippedUsernames` | `List<Object>` | Required | - | List<Object> getSkippedUsernames() | setSkippedUsernames(List<Object> skippedUsernames) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.GroupsMembersJsonResponse2;
import java.io.IOException;
import java.util.Arrays;

GroupsMembersJsonResponse2 groupsMembersJsonResponse2 = new GroupsMembersJsonResponse2.Builder(
    "success8",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
)
.build();
```

