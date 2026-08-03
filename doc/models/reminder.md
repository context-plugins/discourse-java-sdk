
# Reminder

*This model accepts additional fields of type Object.*

## Structure

`Reminder`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Value` | `int` | Required | - | int getValue() | setValue(int value) |
| `Unit` | `String` | Required | - | String getUnit() | setUnit(String unit) |
| `Period` | [`Period`](../../doc/models/period.md) | Required | - | Period getPeriod() | setPeriod(Period period) |
| `Type` | `String` | Required | - | String getType() | setType(String type) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Period;
import com.example.discourse.models.Reminder;
import java.io.IOException;

Reminder reminder = new Reminder.Builder(
    88,
    "unit8",
    Period.BEFORE,
    "type0"
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

