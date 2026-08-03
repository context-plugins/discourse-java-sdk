
# Thumbnail

## Structure

`Thumbnail`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `UploadId` | `Integer` | Optional | - | Integer getUploadId() | setUploadId(Integer uploadId) |
| `Url` | `String` | Optional | - | String getUrl() | setUrl(String url) |
| `Extension` | `String` | Optional | - | String getExtension() | setExtension(String extension) |
| `Width` | `Integer` | Optional | - | Integer getWidth() | setWidth(Integer width) |
| `Height` | `Integer` | Optional | - | Integer getHeight() | setHeight(Integer height) |
| `Filesize` | `Integer` | Optional | - | Integer getFilesize() | setFilesize(Integer filesize) |

## Example

```java
import com.example.discourse.models.Thumbnail;

Thumbnail thumbnail = new Thumbnail.Builder()
    .id(154)
    .uploadId(144)
    .url("url0")
    .extension("extension2")
    .width(2)
    .build();
```

