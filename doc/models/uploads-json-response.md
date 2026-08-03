
# Uploads Json Response

## Structure

`UploadsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Url` | `String` | Required | - | String getUrl() | setUrl(String url) |
| `OriginalFilename` | `String` | Required | - | String getOriginalFilename() | setOriginalFilename(String originalFilename) |
| `Filesize` | `int` | Required | - | int getFilesize() | setFilesize(int filesize) |
| `Width` | `int` | Required | - | int getWidth() | setWidth(int width) |
| `Height` | `int` | Required | - | int getHeight() | setHeight(int height) |
| `ThumbnailWidth` | `int` | Required | - | int getThumbnailWidth() | setThumbnailWidth(int thumbnailWidth) |
| `ThumbnailHeight` | `int` | Required | - | int getThumbnailHeight() | setThumbnailHeight(int thumbnailHeight) |
| `Extension` | `String` | Required | - | String getExtension() | setExtension(String extension) |
| `ShortUrl` | `String` | Required | - | String getShortUrl() | setShortUrl(String shortUrl) |
| `ShortPath` | `String` | Required | - | String getShortPath() | setShortPath(String shortPath) |
| `RetainHours` | `String` | Required | - | String getRetainHours() | setRetainHours(String retainHours) |
| `HumanFilesize` | `String` | Required | - | String getHumanFilesize() | setHumanFilesize(String humanFilesize) |
| `DominantColor` | `String` | Optional | - | String getDominantColor() | setDominantColor(String dominantColor) |
| `Thumbnail` | [`Thumbnail`](../../doc/models/thumbnail.md) | Optional | - | Thumbnail getThumbnail() | setThumbnail(Thumbnail thumbnail) |
| `OptimizedVideo` | [`OptimizedVideo`](../../doc/models/optimized-video.md) | Optional | - | OptimizedVideo getOptimizedVideo() | setOptimizedVideo(OptimizedVideo optimizedVideo) |

## Example

```java
import com.example.discourse.models.OptimizedVideo;
import com.example.discourse.models.Thumbnail;
import com.example.discourse.models.UploadsJsonResponse;

UploadsJsonResponse uploadsJsonResponse = new UploadsJsonResponse.Builder(
    146,
    "url0",
    "original_filename4",
    188,
    10,
    138,
    132,
    220,
    "extension2",
    "short_url6",
    "short_path8",
    "retain_hours2",
    "human_filesize0"
)
.dominantColor("dominant_color0")
.thumbnail(new Thumbnail.Builder()
        .id(154)
        .uploadId(144)
        .url("url0")
        .extension("extension2")
        .width(2)
        .build())
.optimizedVideo(new OptimizedVideo.Builder()
        .id(182)
        .uploadId(116)
        .url("url4")
        .extension("extension6")
        .filesize(152)
        .build())
.build();
```

