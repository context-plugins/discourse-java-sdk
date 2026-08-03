
# Upcoming Changes Stat

## Structure

`UpcomingChangesStat`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `HumanizedName` | `String` | Required | - | String getHumanizedName() | setHumanizedName(String humanizedName) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `Enabled` | `boolean` | Required | - | boolean getEnabled() | setEnabled(boolean enabled) |
| `SpecificGroups` | `List<String>` | Required | - | List<String> getSpecificGroups() | setSpecificGroups(List<String> specificGroups) |
| `Reason` | [`Reason`](../../doc/models/reason.md) | Required | - | Reason getReason() | setReason(Reason reason) |

## Example

```java
import com.example.discourse.models.Reason;
import com.example.discourse.models.UpcomingChangesStat;
import java.util.Arrays;

UpcomingChangesStat upcomingChangesStat = new UpcomingChangesStat.Builder(
    "name4",
    "humanized_name8",
    "description6",
    false,
    Arrays.asList(
        "specific_groups1",
        "specific_groups0"
    ),
    Reason.IN_SPECIFIC_GROUPS
)
.build();
```

