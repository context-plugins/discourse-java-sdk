
# T Invite Group Json Response

*This model accepts additional fields of type Object.*

## Structure

`TInviteGroupJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Group` | [`Group6`](../../doc/models/group-6.md) | Optional | - | Group6 getGroup() | setGroup(Group6 group) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Group6;
import com.example.discourse.models.TInviteGroupJsonResponse;
import java.io.IOException;

TInviteGroupJsonResponse tInviteGroupJsonResponse = new TInviteGroupJsonResponse.Builder()
    .group(new Group6.Builder()
        .id(38)
        .name("name8")
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

