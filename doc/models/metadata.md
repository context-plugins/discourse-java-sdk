
# Metadata

## Structure

`Metadata`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Sha1Checksum` | `String` | Optional | The SHA1 checksum of the upload binary blob. Optionally<br>be provided and serves as an additional security check when<br>later processing the file in complete-external-upload endpoint. | String getSha1Checksum() | setSha1Checksum(String sha1Checksum) |

## Example

```java
import com.example.discourse.models.Metadata;

Metadata metadata = new Metadata.Builder()
    .sha1Checksum("sha1-checksum2")
    .build();
```

