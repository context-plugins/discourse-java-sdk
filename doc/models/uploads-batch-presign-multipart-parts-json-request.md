
# Uploads Batch Presign Multipart Parts Json Request

## Structure

`UploadsBatchPresignMultipartPartsJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `PartNumbers` | `List<Object>` | Required | The part numbers to generate the presigned URLs for,<br>must be between 1 and 10000. | List<Object> getPartNumbers() | setPartNumbers(List<Object> partNumbers) |
| `UniqueIdentifier` | `String` | Required | The unique identifier returned in the original /create-multipart<br>request. | String getUniqueIdentifier() | setUniqueIdentifier(String uniqueIdentifier) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UploadsBatchPresignMultipartPartsJsonRequest;
import java.io.IOException;
import java.util.Arrays;

UploadsBatchPresignMultipartPartsJsonRequest uploadsBatchPresignMultipartPartsJsonRequest = new UploadsBatchPresignMultipartPartsJsonRequest.Builder(
    Arrays.asList(
        ApiHelper.deserialize("1"),
        ApiHelper.deserialize("2"),
        ApiHelper.deserialize("3")
    ),
    "66e86218-80d9-4bda-b4d5-2b6def968705"
)
.build();
```

