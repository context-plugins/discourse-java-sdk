
# Categories Json Request

## Structure

`CategoriesJsonRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Color` | `String` | Optional | - | String getColor() | setColor(String color) |
| `TextColor` | `String` | Optional | - | String getTextColor() | setTextColor(String textColor) |
| `StyleType` | `String` | Optional | - | String getStyleType() | setStyleType(String styleType) |
| `Emoji` | `String` | Optional | - | String getEmoji() | setEmoji(String emoji) |
| `Icon` | `String` | Optional | - | String getIcon() | setIcon(String icon) |
| `ParentCategoryId` | `Integer` | Optional | - | Integer getParentCategoryId() | setParentCategoryId(Integer parentCategoryId) |
| `AllowBadges` | `Boolean` | Optional | - | Boolean getAllowBadges() | setAllowBadges(Boolean allowBadges) |
| `Slug` | `String` | Optional | - | String getSlug() | setSlug(String slug) |
| `TopicFeaturedLinksAllowed` | `Boolean` | Optional | - | Boolean getTopicFeaturedLinksAllowed() | setTopicFeaturedLinksAllowed(Boolean topicFeaturedLinksAllowed) |
| `Permissions` | [`Permissions`](../../doc/models/permissions.md) | Optional | - | Permissions getPermissions() | setPermissions(Permissions permissions) |
| `SearchPriority` | `Integer` | Optional | - | Integer getSearchPriority() | setSearchPriority(Integer searchPriority) |
| `FormTemplateIds` | `List<Object>` | Optional | - | List<Object> getFormTemplateIds() | setFormTemplateIds(List<Object> formTemplateIds) |
| `CategoryLocalizations` | [`List<CategoryLocalization>`](../../doc/models/category-localization.md) | Optional | - | List<CategoryLocalization> getCategoryLocalizations() | setCategoryLocalizations(List<CategoryLocalization> categoryLocalizations) |

## Example

```java
import com.example.discourse.models.CategoriesJsonRequest;

CategoriesJsonRequest categoriesJsonRequest = new CategoriesJsonRequest.Builder(
    "name6"
)
.color("49d9e9")
.textColor("f0fcfd")
.styleType("style_type8")
.emoji("emoji8")
.icon("icon8")
.build();
```

