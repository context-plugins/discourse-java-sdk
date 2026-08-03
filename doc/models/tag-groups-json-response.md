
# Tag Groups Json Response

## Structure

`TagGroupsJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `TagGroups` | [`List<TagGroup>`](../../doc/models/tag-group.md) | Required | - | List<TagGroup> getTagGroups() | setTagGroups(List<TagGroup> tagGroups) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.ParentTag;
import com.example.discourse.models.Tag;
import com.example.discourse.models.TagGroup;
import com.example.discourse.models.TagGroupsJsonResponse;
import java.io.IOException;
import java.util.Arrays;
import java.util.LinkedHashMap;

TagGroupsJsonResponse tagGroupsJsonResponse = new TagGroupsJsonResponse.Builder(
    Arrays.asList(
        new TagGroup.Builder(
            140,
            "name0",
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
            new LinkedHashMap<String, Integer>() {{
                put("key0", 223);
                put("key1", 224);
                put("key2", 225);
            }}
        )
        .build()
    )
)
.build();
```

