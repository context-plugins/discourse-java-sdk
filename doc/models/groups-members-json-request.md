
# Groups Members Json Request

## Structure

`GroupsMembersJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Usernames` | `String` | Optional | comma separated list | String getUsernames() | setUsernames(String usernames) |

## Example

```java
import com.example.discourse.models.GroupsMembersJsonRequest;

GroupsMembersJsonRequest groupsMembersJsonRequest = new GroupsMembersJsonRequest.Builder()
    .usernames("username1,username2")
    .build();
```

