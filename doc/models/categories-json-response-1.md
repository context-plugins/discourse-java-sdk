
# Categories Json Response 1

## Structure

`CategoriesJsonResponse1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `CategoryList` | [`CategoryList`](../../doc/models/category-list.md) | Required | - | CategoryList getCategoryList() | setCategoryList(CategoryList categoryList) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.CategoriesJsonResponse1;
import com.example.discourse.models.Category1;
import com.example.discourse.models.CategoryList;
import java.io.IOException;
import java.util.Arrays;

CategoriesJsonResponse1 categoriesJsonResponse1 = new CategoriesJsonResponse1.Builder(
    new CategoryList.Builder(
        false,
        false,
        Arrays.asList(
            new Category1.Builder(
                16,
                "name8",
                "color2",
                "text_color0",
                "style_type0",
                "emoji0",
                "icon0",
                "slug2",
                172,
                244,
                46,
                "description8",
                "description_text0",
                "description_excerpt8",
                "topic_url0",
                false,
                54,
                112,
                false,
                "topic_template6",
                "topic_title_placeholder4",
                false,
                74,
                "sort_order8",
                "sort_ascending8",
                false,
                140,
                "default_view2",
                "subcategory_list_style4",
                "default_top_period2",
                "default_list_filter6",
                172,
                false,
                50,
                152,
                6,
                54,
                162,
                Arrays.asList(
                    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
                ),
                "uploaded_logo6",
                "uploaded_logo_dark4",
                "uploaded_background2",
                "uploaded_background_dark2"
            )
            .isUncategorized(false)
            .subcategoryList(Arrays.asList(
                    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
                ))
            .build()
        )
    )
    .build()
)
.build();
```

