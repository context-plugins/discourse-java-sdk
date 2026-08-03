
# Category 4

## Structure

`Category4`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Color` | `String` | Required | - | String getColor() | setColor(String color) |
| `TextColor` | `String` | Required | - | String getTextColor() | setTextColor(String textColor) |
| `StyleType` | `String` | Optional | - | String getStyleType() | setStyleType(String styleType) |
| `Emoji` | `String` | Optional | - | String getEmoji() | setEmoji(String emoji) |
| `Icon` | `String` | Optional | - | String getIcon() | setIcon(String icon) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `TopicCount` | `int` | Required | - | int getTopicCount() | setTopicCount(int topicCount) |
| `PostCount` | `int` | Required | - | int getPostCount() | setPostCount(int postCount) |
| `Position` | `int` | Required | - | int getPosition() | setPosition(int position) |
| `Description` | `String` | Optional | - | String getDescription() | setDescription(String description) |
| `DescriptionText` | `String` | Optional | - | String getDescriptionText() | setDescriptionText(String descriptionText) |
| `DescriptionExcerpt` | `String` | Optional | - | String getDescriptionExcerpt() | setDescriptionExcerpt(String descriptionExcerpt) |
| `TopicUrl` | `String` | Required | - | String getTopicUrl() | setTopicUrl(String topicUrl) |
| `ReadRestricted` | `boolean` | Required | - | boolean getReadRestricted() | setReadRestricted(boolean readRestricted) |
| `Permission` | `int` | Required | - | int getPermission() | setPermission(int permission) |
| `NotificationLevel` | `int` | Required | - | int getNotificationLevel() | setNotificationLevel(int notificationLevel) |
| `TopicTemplate` | `String` | Required | - | String getTopicTemplate() | setTopicTemplate(String topicTemplate) |
| `TopicTitlePlaceholder` | `String` | Required | - | String getTopicTitlePlaceholder() | setTopicTitlePlaceholder(String topicTitlePlaceholder) |
| `HasChildren` | `boolean` | Required | - | boolean getHasChildren() | setHasChildren(boolean hasChildren) |
| `SubcategoryCount` | `Integer` | Required | - | Integer getSubcategoryCount() | setSubcategoryCount(Integer subcategoryCount) |
| `SortOrder` | `String` | Required | - | String getSortOrder() | setSortOrder(String sortOrder) |
| `SortAscending` | `String` | Required | - | String getSortAscending() | setSortAscending(String sortAscending) |
| `ShowSubcategoryList` | `boolean` | Required | - | boolean getShowSubcategoryList() | setShowSubcategoryList(boolean showSubcategoryList) |
| `NumFeaturedTopics` | `int` | Required | - | int getNumFeaturedTopics() | setNumFeaturedTopics(int numFeaturedTopics) |
| `DefaultView` | `String` | Required | - | String getDefaultView() | setDefaultView(String defaultView) |
| `SubcategoryListStyle` | `String` | Required | - | String getSubcategoryListStyle() | setSubcategoryListStyle(String subcategoryListStyle) |
| `DefaultTopPeriod` | `String` | Required | - | String getDefaultTopPeriod() | setDefaultTopPeriod(String defaultTopPeriod) |
| `DefaultListFilter` | `String` | Required | - | String getDefaultListFilter() | setDefaultListFilter(String defaultListFilter) |
| `MinimumRequiredTags` | `int` | Required | - | int getMinimumRequiredTags() | setMinimumRequiredTags(int minimumRequiredTags) |
| `NavigateToFirstPostAfterRead` | `boolean` | Required | - | boolean getNavigateToFirstPostAfterRead() | setNavigateToFirstPostAfterRead(boolean navigateToFirstPostAfterRead) |
| `AllowedTags` | `List<Object>` | Required | - | List<Object> getAllowedTags() | setAllowedTags(List<Object> allowedTags) |
| `AllowedTagGroups` | `List<Object>` | Required | - | List<Object> getAllowedTagGroups() | setAllowedTagGroups(List<Object> allowedTagGroups) |
| `AllowGlobalTags` | `boolean` | Required | - | boolean getAllowGlobalTags() | setAllowGlobalTags(boolean allowGlobalTags) |
| `RequiredTagGroups` | [`List<RequiredTagGroup>`](../../doc/models/required-tag-group.md) | Required | - | List<RequiredTagGroup> getRequiredTagGroups() | setRequiredTagGroups(List<RequiredTagGroup> requiredTagGroups) |
| `ReadOnlyBanner` | `String` | Required | - | String getReadOnlyBanner() | setReadOnlyBanner(String readOnlyBanner) |
| `UploadedLogo` | `String` | Required | - | String getUploadedLogo() | setUploadedLogo(String uploadedLogo) |
| `UploadedLogoDark` | `String` | Required | - | String getUploadedLogoDark() | setUploadedLogoDark(String uploadedLogoDark) |
| `UploadedBackground` | `String` | Required | - | String getUploadedBackground() | setUploadedBackground(String uploadedBackground) |
| `UploadedBackgroundDark` | `String` | Required | - | String getUploadedBackgroundDark() | setUploadedBackgroundDark(String uploadedBackgroundDark) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `CustomFields` | `Object` | Optional | - | Object getCustomFields() | setCustomFields(Object customFields) |
| `ParentCategoryId` | `Integer` | Optional | - | Integer getParentCategoryId() | setParentCategoryId(Integer parentCategoryId) |
| `FormTemplateIds` | `List<Object>` | Optional | - | List<Object> getFormTemplateIds() | setFormTemplateIds(List<Object> formTemplateIds) |
| `CategoryTypes` | `Object` | Optional | - | Object getCategoryTypes() | setCategoryTypes(Object categoryTypes) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Category4;
import com.example.discourse.models.RequiredTagGroup;
import java.io.IOException;
import java.util.Arrays;

Category4 category4 = new Category4.Builder(
    84,
    "name8",
    "color2",
    "text_color0",
    "slug2",
    240,
    56,
    114,
    "topic_url0",
    false,
    122,
    180,
    "topic_template6",
    "topic_title_placeholder4",
    false,
    6,
    "sort_order8",
    "sort_ascending8",
    false,
    72,
    "default_view2",
    "subcategory_list_style4",
    "default_top_period2",
    "default_list_filter6",
    152,
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    false,
    Arrays.asList(
        new RequiredTagGroup.Builder(
            "name4",
            58
        )
        .build()
    ),
    "read_only_banner2",
    "uploaded_logo6",
    "uploaded_logo_dark4",
    "uploaded_background2",
    "uploaded_background_dark2",
    false
)
.styleType("style_type0")
.emoji("emoji0")
.icon("icon0")
.description("description8")
.descriptionText("description_text0")
.build();
```

