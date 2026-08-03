
# Uploads Abort Multipart Json Request

## Structure

`UploadsAbortMultipartJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `ExternalUploadIdentifier` | `String` | Required | The identifier of the multipart upload in the external<br>storage provider. This is the multipart upload_id in AWS S3. | String getExternalUploadIdentifier() | setExternalUploadIdentifier(String externalUploadIdentifier) |

## Example

```java
import com.example.discourse.models.UploadsAbortMultipartJsonRequest;

UploadsAbortMultipartJsonRequest uploadsAbortMultipartJsonRequest = new UploadsAbortMultipartJsonRequest.Builder(
    "84x83tmxy398t3y._Q_z8CoJYVr69bE6D7f8J6Oo0434QquLFoYdGVerWFx9X5HDEI_TP_95c34n853495x35345394.d.ghQ"
)
.build();
```

