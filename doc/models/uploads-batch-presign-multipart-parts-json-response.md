
# Uploads Batch Presign Multipart Parts Json Response

## Structure

`UploadsBatchPresignMultipartPartsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `PresignedUrls` | `Object` | Required | The presigned URLs for each part number, which has<br>the part numbers as keys. | Object getPresignedUrls() | setPresignedUrls(Object presignedUrls) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.UploadsBatchPresignMultipartPartsJsonResponse;
import java.io.IOException;

UploadsBatchPresignMultipartPartsJsonResponse uploadsBatchPresignMultipartPartsJsonResponse = new UploadsBatchPresignMultipartPartsJsonResponse.Builder(
    ApiHelper.deserialize("{\"1\":\"https://discourse-martin-uploads-test.s3.us-east-2.amazonaws.com/temp/uploads/default/123abc/123abc.jpg?partNumber=1&uploadId=123456abcd&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=test&X-Amz-Date=20211222T012336Z&X-Amz-Expires=600&X-Amz-SignedHeaders=host&X-Amz-Signature=abc123\"}")
)
.build();
```

