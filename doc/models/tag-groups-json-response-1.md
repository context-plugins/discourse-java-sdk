
# Tag Groups Json Response 1

## Structure

`TagGroupsJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `TagGroup` | [`TagGroup1`](../../doc/models/tag-group-1.md) | Required | - | TagGroup1 getTagGroup() | setTagGroup(TagGroup1 tagGroup) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ParentTag;
import com.example.discourse.models.Tag;
import com.example.discourse.models.TagGroup1;
import com.example.discourse.models.TagGroupsJsonResponse1;
import java.io.IOException;
import java.util.Arrays;

TagGroupsJsonResponse1 tagGroupsJsonResponse1 = new TagGroupsJsonResponse1.Builder(
    new TagGroup1.Builder(
        164,
        "name4",
        Arrays.asList(
            new Tag.Builder(
                26,
                "name0",
                "slug4"
            )
            .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
            .build()
        ),
        Arrays.asList(
            new ParentTag.Builder(
                110,
                "name2",
                "slug6"
            )
            .build()
        ),
        false,
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    )
    .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
    .build()
)
.build();
```

