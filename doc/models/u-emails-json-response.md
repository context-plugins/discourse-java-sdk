
# U Emails Json Response

## Structure

`UEmailsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Email` | `String` | Required | - | String getEmail() | setEmail(String email) |
| `SecondaryEmails` | `List<Object>` | Required | - | List<Object> getSecondaryEmails() | setSecondaryEmails(List<Object> secondaryEmails) |
| `UnconfirmedEmails` | `List<Object>` | Required | - | List<Object> getUnconfirmedEmails() | setUnconfirmedEmails(List<Object> unconfirmedEmails) |
| `AssociatedAccounts` | `List<Object>` | Required | - | List<Object> getAssociatedAccounts() | setAssociatedAccounts(List<Object> associatedAccounts) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UEmailsJsonResponse;
import java.io.IOException;
import java.util.Arrays;

UEmailsJsonResponse uEmailsJsonResponse = new UEmailsJsonResponse.Builder(
    "email0",
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
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

