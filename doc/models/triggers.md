
# Triggers

## Structure

`Triggers`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UserChange` | `int` | Required | - | int getUserChange() | setUserChange(int userChange) |
| `None` | `int` | Required | - | int getNone() | setNone(int none) |
| `PostRevision` | `int` | Required | - | int getPostRevision() | setPostRevision(int postRevision) |
| `TrustLevelChange` | `int` | Required | - | int getTrustLevelChange() | setTrustLevelChange(int trustLevelChange) |
| `PostAction` | `int` | Required | - | int getPostAction() | setPostAction(int postAction) |

## Example

```java
import com.example.discourse.models.Triggers;

Triggers triggers = new Triggers.Builder(
    26,
    198,
    74,
    164,
    132
)
.build();
```

