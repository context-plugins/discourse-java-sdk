
# Custom Fields

## Structure

`CustomFields`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `FirstName` | `String` | Optional | - | String getFirstName() | setFirstName(String firstName) |

## Example

```java
import com.example.discourse.models.CustomFields;

CustomFields customFields = new CustomFields.Builder()
    .firstName("first_name0")
    .build();
```

