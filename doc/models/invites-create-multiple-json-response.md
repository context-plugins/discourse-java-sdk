
# Invites Create Multiple Json Response

*This model accepts additional fields of type Object.*

## Structure

`InvitesCreateMultipleJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `NumSuccessfullyCreatedInvitations` | `Integer` | Optional | - | Integer getNumSuccessfullyCreatedInvitations() | setNumSuccessfullyCreatedInvitations(Integer numSuccessfullyCreatedInvitations) |
| `NumFailedInvitations` | `Integer` | Optional | - | Integer getNumFailedInvitations() | setNumFailedInvitations(Integer numFailedInvitations) |
| `FailedInvitations` | `List<Object>` | Optional | - | List<Object> getFailedInvitations() | setFailedInvitations(List<Object> failedInvitations) |
| `SuccessfulInvitations` | `List<Object>` | Optional | - | List<Object> getSuccessfulInvitations() | setSuccessfulInvitations(List<Object> successfulInvitations) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.InvitesCreateMultipleJsonResponse;
import java.io.IOException;
import java.util.Arrays;

InvitesCreateMultipleJsonResponse invitesCreateMultipleJsonResponse = new InvitesCreateMultipleJsonResponse.Builder()
    .numSuccessfullyCreatedInvitations(42)
    .numFailedInvitations(42)
    .failedInvitations(Arrays.asList(

    ))
    .successfulInvitations(Arrays.asList(
        ApiHelper.deserialize("{\"id\":42,\"link\":\"http://example.com/invites/9045fd767efe201ca60c6658bcf14158\",\"email\":\"not-a-user-yet-1@example.com\",\"emailed\":true,\"custom_message\":\"Hello world!\",\"topics\":[],\"groups\":[],\"created_at\":\"2021-01-01T12:00:00.000Z\",\"updated_at\":\"2021-01-01T12:00:00.000Z\",\"expires_at\":\"2021-02-01T12:00:00.000Z\",\"expired\":false}"),
        ApiHelper.deserialize("{\"id\":42,\"link\":\"http://example.com/invites/c6658bcf141589045fd767efe201ca60\",\"email\":\"not-a-user-yet-2@example.com\",\"emailed\":true,\"custom_message\":\"Hello world!\",\"topics\":[],\"groups\":[],\"created_at\":\"2021-01-01T12:00:00.000Z\",\"updated_at\":\"2021-01-01T12:00:00.000Z\",\"expires_at\":\"2021-02-01T12:00:00.000Z\",\"expired\":false}")
    ))
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

