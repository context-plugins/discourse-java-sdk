
# Tag Groups Json Response 3

*This model accepts additional fields of type Object.*

## Structure

`TagGroupsJsonResponse3`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Optional | - | String getSuccess() | setSuccess(String success) |
| `TagGroup` | [`TagGroup2`](../../doc/models/tag-group-2.md) | Optional | - | TagGroup2 getTagGroup() | setTagGroup(TagGroup2 tagGroup) |
| `AdditionalProperties` | `Map<String, Object>` | Optional | - | Object getAdditionalProperty(String key) | additionalProperty(String key, Object value) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.TagGroup2;
import com.example.discourse.models.TagGroupsJsonResponse3;
import java.io.IOException;
import java.util.Arrays;

TagGroupsJsonResponse3 tagGroupsJsonResponse3 = new TagGroupsJsonResponse3.Builder()
    .success("success0")
    .tagGroup(new TagGroup2.Builder()
        .id(164)
        .name("name4")
        .tagNames(Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ))
        .parentTagName(Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ))
        .onePerTopic(false)
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build())
.additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build();
```

