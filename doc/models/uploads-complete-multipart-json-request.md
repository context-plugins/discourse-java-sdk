
# Uploads Complete Multipart Json Request

## Structure

`UploadsCompleteMultipartJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UniqueIdentifier` | `String` | Required | The unique identifier returned in the original /create-multipart<br>request. | String getUniqueIdentifier() | setUniqueIdentifier(String uniqueIdentifier) |
| `Parts` | `List<Object>` | Required | All of the part numbers and their corresponding ETags<br>that have been uploaded must be provided. | List<Object> getParts() | setParts(List<Object> parts) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UploadsCompleteMultipartJsonRequest;
import java.io.IOException;
import java.util.Arrays;

UploadsCompleteMultipartJsonRequest uploadsCompleteMultipartJsonRequest = new UploadsCompleteMultipartJsonRequest.Builder(
    "66e86218-80d9-4bda-b4d5-2b6def968705",
    Arrays.asList(
        ApiHelper.deserialize("{\"part_number\":1,\"etag\":\"0c376dcfcc2606f4335bbc732de93344\"}"),
        ApiHelper.deserialize("{\"part_number\":2,\"etag\":\"09ert8cfcc2606f4335bbc732de91122\"}")
    )
)
.build();
```

