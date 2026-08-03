
# Uploads Create Multipart Json Request

## Structure

`UploadsCreateMultipartJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UploadType` | [`UploadType1`](../../doc/models/upload-type-1.md) | Required | - | UploadType1 getUploadType() | setUploadType(UploadType1 uploadType) |
| `FileName` | `String` | Required | - | String getFileName() | setFileName(String fileName) |
| `FileSize` | `int` | Required | File size should be represented in bytes. | int getFileSize() | setFileSize(int fileSize) |
| `Metadata` | [`Metadata`](../../doc/models/metadata.md) | Optional | - | Metadata getMetadata() | setMetadata(Metadata metadata) |

## Example

```java
import com.example.discourse.models.Metadata;
import com.example.discourse.models.UploadType1;
import com.example.discourse.models.UploadsCreateMultipartJsonRequest;

UploadsCreateMultipartJsonRequest uploadsCreateMultipartJsonRequest = new UploadsCreateMultipartJsonRequest.Builder(
    UploadType1.CUSTOM_EMOJI,
    "IMG_2021.jpeg",
    4096
)
.metadata(new Metadata.Builder()
        .sha1Checksum("sha1-checksum2")
        .build())
.build();
```

