
# T Invite Group Json Request

*This model accepts additional fields of type Object.*

## Structure

`TInviteGroupJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Group` | `String` | Optional | The name of the group to invite | String getGroup() | setGroup(String group) |
| `ShouldNotify` | `Boolean` | Optional | Whether to notify the group, it defaults to true | Boolean getShouldNotify() | setShouldNotify(Boolean shouldNotify) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TInviteGroupJsonRequest;
import java.io.IOException;

TInviteGroupJsonRequest tInviteGroupJsonRequest = new TInviteGroupJsonRequest.Builder()
    .group("group6")
    .shouldNotify(false)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

