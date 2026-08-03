
# Optimized Video

## Structure

`OptimizedVideo`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `Integer` | Optional | - | Integer getId() | setId(Integer id) |
| `UploadId` | `Integer` | Optional | - | Integer getUploadId() | setUploadId(Integer uploadId) |
| `Url` | `String` | Optional | - | String getUrl() | setUrl(String url) |
| `Extension` | `String` | Optional | - | String getExtension() | setExtension(String extension) |
| `Filesize` | `Integer` | Optional | - | Integer getFilesize() | setFilesize(Integer filesize) |
| `Sha1` | `String` | Optional | - | String getSha1() | setSha1(String sha1) |
| `OriginalFilename` | `String` | Optional | - | String getOriginalFilename() | setOriginalFilename(String originalFilename) |

## Example

```java
import com.example.discourse.models.OptimizedVideo;

OptimizedVideo optimizedVideo = new OptimizedVideo.Builder()
    .id(86)
    .uploadId(212)
    .url("url6")
    .extension("extension8")
    .filesize(248)
    .build();
```

