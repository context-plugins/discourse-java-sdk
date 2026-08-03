
# Trust Levels

## Structure

`TrustLevels`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Newuser` | `int` | Required | - | int getNewuser() | setNewuser(int newuser) |
| `Basic` | `int` | Required | - | int getBasic() | setBasic(int basic) |
| `Member` | `int` | Required | - | int getMember() | setMember(int member) |
| `Regular` | `int` | Required | - | int getRegular() | setRegular(int regular) |
| `Leader` | `int` | Required | - | int getLeader() | setLeader(int leader) |

## Example

```java
import com.example.discourse.models.TrustLevels;

TrustLevels trustLevels = new TrustLevels.Builder(
    26,
    246,
    104,
    114,
    156
)
.build();
```

