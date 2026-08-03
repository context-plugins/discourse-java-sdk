
# Category 1

## Structure

`Category1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `int` | Required | - | int getId() | setId(int id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Color` | `String` | Required | - | String getColor() | setColor(String color) |
| `TextColor` | `String` | Required | - | String getTextColor() | setTextColor(String textColor) |
| `StyleType` | `String` | Required | - | String getStyleType() | setStyleType(String styleType) |
| `Emoji` | `String` | Required | - | String getEmoji() | setEmoji(String emoji) |
| `Icon` | `String` | Required | - | String getIcon() | setIcon(String icon) |
| `Slug` | `String` | Required | - | String getSlug() | setSlug(String slug) |
| `TopicCount` | `int` | Required | - | int getTopicCount() | setTopicCount(int topicCount) |
| `PostCount` | `int` | Required | - | int getPostCount() | setPostCount(int postCount) |
| `Position` | `int` | Required | - | int getPosition() | setPosition(int position) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `DescriptionText` | `String` | Required | - | String getDescriptionText() | setDescriptionText(String descriptionText) |
| `DescriptionExcerpt` | `String` | Required | - | String getDescriptionExcerpt() | setDescriptionExcerpt(String descriptionExcerpt) |
| `TopicUrl` | `String` | Required | - | String getTopicUrl() | setTopicUrl(String topicUrl) |
| `ReadRestricted` | `boolean` | Required | - | boolean getReadRestricted() | setReadRestricted(boolean readRestricted) |
| `Permission` | `int` | Required | - | int getPermission() | setPermission(int permission) |
| `NotificationLevel` | `int` | Required | - | int getNotificationLevel() | setNotificationLevel(int notificationLevel) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
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
| `TopicsDay` | `int` | Required | - | int getTopicsDay() | setTopicsDay(int topicsDay) |
| `TopicsWeek` | `int` | Required | - | int getTopicsWeek() | setTopicsWeek(int topicsWeek) |
| `TopicsMonth` | `int` | Required | - | int getTopicsMonth() | setTopicsMonth(int topicsMonth) |
| `TopicsYear` | `int` | Required | - | int getTopicsYear() | setTopicsYear(int topicsYear) |
| `TopicsAllTime` | `int` | Required | - | int getTopicsAllTime() | setTopicsAllTime(int topicsAllTime) |
| `IsUncategorized` | `Boolean` | Optional | - | Boolean getIsUncategorized() | setIsUncategorized(Boolean isUncategorized) |
| `SubcategoryIds` | `List<Object>` | Required | - | List<Object> getSubcategoryIds() | setSubcategoryIds(List<Object> subcategoryIds) |
| `SubcategoryList` | `List<Object>` | Optional | - | List<Object> getSubcategoryList() | setSubcategoryList(List<Object> subcategoryList) |
| `UploadedLogo` | `String` | Required | - | String getUploadedLogo() | setUploadedLogo(String uploadedLogo) |
| `UploadedLogoDark` | `String` | Required | - | String getUploadedLogoDark() | setUploadedLogoDark(String uploadedLogoDark) |
| `UploadedBackground` | `String` | Required | - | String getUploadedBackground() | setUploadedBackground(String uploadedBackground) |
| `UploadedBackgroundDark` | `String` | Required | - | String getUploadedBackgroundDark() | setUploadedBackgroundDark(String uploadedBackgroundDark) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Category1;
import java.io.IOException;
import java.util.Arrays;

Category1 category1 = new Category1.Builder(
    216,
    "name0",
    "color6",
    "text_color2",
    "style_type2",
    "emoji2",
    "icon2",
    "slug6",
    116,
    188,
    246,
    "description0",
    "description_text8",
    "description_excerpt0",
    "topic_url8",
    false,
    254,
    56,
    false,
    "topic_template8",
    "topic_title_placeholder4",
    false,
    130,
    "sort_order0",
    "sort_ascending0",
    false,
    196,
    "default_view6",
    "subcategory_list_style6",
    "default_top_period6",
    "default_list_filter2",
    228,
    false,
    250,
    96,
    50,
    110,
    150,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    "uploaded_logo8",
    "uploaded_logo_dark4",
    "uploaded_background4",
    "uploaded_background_dark6"
)
.isUncategorized(false)
.subcategoryList(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.build();
```

