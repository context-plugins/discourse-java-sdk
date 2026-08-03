
# Categories Json Response 2

## Structure

`CategoriesJsonResponse2`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Success` | `String` | Required | - | String getSuccess() | setSuccess(String success) |
| `Category` | [`Category2`](../../doc/models/category-2.md) | Required | - | Category2 getCategory() | setCategory(Category2 category) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.CategoriesJsonResponse2;
import com.example.discourse.models.Category2;
import com.example.discourse.models.GroupPermission;
import com.example.discourse.models.RequiredTagGroup;
import java.io.IOException;
import java.util.Arrays;

CategoriesJsonResponse2 categoriesJsonResponse2 = new CategoriesJsonResponse2.Builder(
    "success0",
    new Category2.Builder(
        232,
        "name2",
        "color4",
        "text_color4",
        "slug4",
        132,
        204,
        6,
        "description8",
        "description_text6",
        "description_excerpt2",
        "topic_url6",
        false,
        14,
        72,
        false,
        "topic_template0",
        "topic_title_placeholder2",
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        false,
        114,
        "sort_order2",
        "sort_ascending2",
        false,
        180,
        "default_view4",
        "subcategory_list_style8",
        "default_top_period4",
        "default_list_filter0",
        212,
        false,
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        Arrays.asList(
            new RequiredTagGroup.Builder(
                "name4",
                58
            )
            .build()
        ),
        "read_only_banner4",
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        "auto_close_hours2",
        false,
        false,
        "default_slow_mode_seconds6",
        Arrays.asList(
            new GroupPermission.Builder(
                146,
                "group_name4",
                230
            )
            .build()
        ),
        "email_in8",
        false,
        false,
        false,
        false,
        false,
        false,
        172,
        Arrays.asList(
            197
        ),
        Arrays.asList(
            14,
            15,
            16
        ),
        "uploaded_logo0",
        "uploaded_logo_dark2",
        "uploaded_background6",
        "uploaded_background_dark4"
    )
    .styleType("style_type4")
    .emoji("emoji4")
    .icon("icon6")
    .locale("locale0")
    .allowedTags(Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ))
    .build()
)
.build();
```

