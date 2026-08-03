
# Uploads Complete External Upload Json Request

## Structure

`UploadsCompleteExternalUploadJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UniqueIdentifier` | `String` | Required | The unique identifier returned in the original /generate-presigned-put<br>request. | String getUniqueIdentifier() | setUniqueIdentifier(String uniqueIdentifier) |
| `ForPrivateMessage` | `String` | Optional | Optionally set this to true if the upload is for a<br>private message. | String getForPrivateMessage() | setForPrivateMessage(String forPrivateMessage) |
| `ForSiteSetting` | `String` | Optional | Optionally set this to true if the upload is for a<br>site setting. | String getForSiteSetting() | setForSiteSetting(String forSiteSetting) |
| `Pasted` | `String` | Optional | Optionally set this to true if the upload was pasted<br>into the upload area. This will convert PNG files to JPEG. | String getPasted() | setPasted(String pasted) |

## Example

```java
import com.example.discourse.models.UploadsCompleteExternalUploadJsonRequest;

UploadsCompleteExternalUploadJsonRequest uploadsCompleteExternalUploadJsonRequest = new UploadsCompleteExternalUploadJsonRequest.Builder(
    "66e86218-80d9-4bda-b4d5-2b6def968705"
)
.forPrivateMessage("true")
.forSiteSetting("true")
.pasted("true")
.build();
```

