
# Uploads Generate Presigned Put Json Request

## Structure

`UploadsGeneratePresignedPutJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Type` | [`Type`](../../doc/models/type.md) | Required | - | Type getType() | setType(Type type) |
| `FileName` | `String` | Required | - | String getFileName() | setFileName(String fileName) |
| `FileSize` | `int` | Required | File size should be represented in bytes. | int getFileSize() | setFileSize(int fileSize) |
| `Metadata` | [`Metadata`](../../doc/models/metadata.md) | Optional | - | Metadata getMetadata() | setMetadata(Metadata metadata) |

## Example

```java
import com.example.discourse.models.Metadata;
import com.example.discourse.models.Type;
import com.example.discourse.models.UploadsGeneratePresignedPutJsonRequest;

UploadsGeneratePresignedPutJsonRequest uploadsGeneratePresignedPutJsonRequest = new UploadsGeneratePresignedPutJsonRequest.Builder(
    Type.CARD_BACKGROUND,
    "IMG_2021.jpeg",
    4096
)
.metadata(new Metadata.Builder()
        .sha1Checksum("sha1-checksum2")
        .build())
.build();
```

