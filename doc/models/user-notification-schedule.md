
# User Notification Schedule

## Structure

`UserNotificationSchedule`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Enabled` | `boolean` | Required | - | boolean getEnabled() | setEnabled(boolean enabled) |
| `Day0StartTime` | `int` | Required | - | int getDay0StartTime() | setDay0StartTime(int day0StartTime) |
| `Day0EndTime` | `int` | Required | - | int getDay0EndTime() | setDay0EndTime(int day0EndTime) |
| `Day1StartTime` | `int` | Required | - | int getDay1StartTime() | setDay1StartTime(int day1StartTime) |
| `Day1EndTime` | `int` | Required | - | int getDay1EndTime() | setDay1EndTime(int day1EndTime) |
| `Day2StartTime` | `int` | Required | - | int getDay2StartTime() | setDay2StartTime(int day2StartTime) |
| `Day2EndTime` | `int` | Required | - | int getDay2EndTime() | setDay2EndTime(int day2EndTime) |
| `Day3StartTime` | `int` | Required | - | int getDay3StartTime() | setDay3StartTime(int day3StartTime) |
| `Day3EndTime` | `int` | Required | - | int getDay3EndTime() | setDay3EndTime(int day3EndTime) |
| `Day4StartTime` | `int` | Required | - | int getDay4StartTime() | setDay4StartTime(int day4StartTime) |
| `Day4EndTime` | `int` | Required | - | int getDay4EndTime() | setDay4EndTime(int day4EndTime) |
| `Day5StartTime` | `int` | Required | - | int getDay5StartTime() | setDay5StartTime(int day5StartTime) |
| `Day5EndTime` | `int` | Required | - | int getDay5EndTime() | setDay5EndTime(int day5EndTime) |
| `Day6StartTime` | `int` | Required | - | int getDay6StartTime() | setDay6StartTime(int day6StartTime) |
| `Day6EndTime` | `int` | Required | - | int getDay6EndTime() | setDay6EndTime(int day6EndTime) |

## Example

```java
import com.example.discourse.models.UserNotificationSchedule;

UserNotificationSchedule userNotificationSchedule = new UserNotificationSchedule.Builder(
    false,
    254,
    38,
    114,
    230,
    128,
    196,
    144,
    94,
    170,
    28,
    32,
    80,
    138,
    192
)
.build();
```

