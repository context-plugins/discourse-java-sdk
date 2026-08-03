
# Admin Backups Json Response

*This model accepts additional fields of type Object.*

## Structure

`AdminBackupsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Filename` | `String` | Required | - | String getFilename() | setFilename(String filename) |
| `Size` | `int` | Required | - | int getSize() | setSize(int size) |
| `LastModified` | `String` | Required | - | String getLastModified() | setLastModified(String lastModified) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.AdminBackupsJsonResponse;
import java.io.IOException;

AdminBackupsJsonResponse adminBackupsJsonResponse = new AdminBackupsJsonResponse.Builder(
    "filename8",
    182,
    "last_modified8"
)
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

