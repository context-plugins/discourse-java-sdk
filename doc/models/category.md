
# Category

## Structure

`Category`

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
| `Locale` | `String` | Optional | - | String getLocale() | setLocale(String locale) |
| `TopicCount` | `int` | Required | - | int getTopicCount() | setTopicCount(int topicCount) |
| `PostCount` | `int` | Required | - | int getPostCount() | setPostCount(int postCount) |
| `Position` | `int` | Required | - | int getPosition() | setPosition(int position) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `DescriptionText` | `String` | Required | - | String getDescriptionText() | setDescriptionText(String descriptionText) |
| `DescriptionExcerpt` | `String` | Required | - | String getDescriptionExcerpt() | setDescriptionExcerpt(String descriptionExcerpt) |
| `TopicUrl` | `String` | Required | - | String getTopicUrl() | setTopicUrl(String topicUrl) |
| `ReadRestricted` | `boolean` | Required | - | boolean getReadRestricted() | setReadRestricted(boolean readRestricted) |
| `Permission` | `Integer` | Required | - | Integer getPermission() | setPermission(Integer permission) |
| `NotificationLevel` | `int` | Required | - | int getNotificationLevel() | setNotificationLevel(int notificationLevel) |
| `CanEdit` | `boolean` | Required | - | boolean getCanEdit() | setCanEdit(boolean canEdit) |
| `TopicTemplate` | `String` | Required | - | String getTopicTemplate() | setTopicTemplate(String topicTemplate) |
| `TopicTitlePlaceholder` | `String` | Required | - | String getTopicTitlePlaceholder() | setTopicTitlePlaceholder(String topicTitlePlaceholder) |
| `FormTemplateIds` | `List<Object>` | Optional | - | List<Object> getFormTemplateIds() | setFormTemplateIds(List<Object> formTemplateIds) |
| `HasChildren` | `Boolean` | Required | - | Boolean getHasChildren() | setHasChildren(Boolean hasChildren) |
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
| `CustomFields` | `Object` | Required | - | Object getCustomFields() | setCustomFields(Object customFields) |
| `AllowedTags` | `List<Object>` | Optional | - | List<Object> getAllowedTags() | setAllowedTags(List<Object> allowedTags) |
| `AllowedTagGroups` | `List<Object>` | Optional | - | List<Object> getAllowedTagGroups() | setAllowedTagGroups(List<Object> allowedTagGroups) |
| `AllowGlobalTags` | `Boolean` | Optional | - | Boolean getAllowGlobalTags() | setAllowGlobalTags(Boolean allowGlobalTags) |
| `RequiredTagGroups` | [`List<RequiredTagGroup>`](../../doc/models/required-tag-group.md) | Required | - | List<RequiredTagGroup> getRequiredTagGroups() | setRequiredTagGroups(List<RequiredTagGroup> requiredTagGroups) |
| `CategorySetting` | [`CategorySetting`](../../doc/models/category-setting.md) | Optional | - | CategorySetting getCategorySetting() | setCategorySetting(CategorySetting categorySetting) |
| `CategoryLocalizations` | `List<Object>` | Optional | - | List<Object> getCategoryLocalizations() | setCategoryLocalizations(List<Object> categoryLocalizations) |
| `ReadOnlyBanner` | `String` | Required | - | String getReadOnlyBanner() | setReadOnlyBanner(String readOnlyBanner) |
| `AvailableGroups` | `List<Object>` | Required | - | List<Object> getAvailableGroups() | setAvailableGroups(List<Object> availableGroups) |
| `AutoCloseHours` | `String` | Required | - | String getAutoCloseHours() | setAutoCloseHours(String autoCloseHours) |
| `AutoCloseBasedOnLastPost` | `boolean` | Required | - | boolean getAutoCloseBasedOnLastPost() | setAutoCloseBasedOnLastPost(boolean autoCloseBasedOnLastPost) |
| `AllowUnlimitedOwnerEditsOnFirstPost` | `boolean` | Required | - | boolean getAllowUnlimitedOwnerEditsOnFirstPost() | setAllowUnlimitedOwnerEditsOnFirstPost(boolean allowUnlimitedOwnerEditsOnFirstPost) |
| `DefaultSlowModeSeconds` | `String` | Required | - | String getDefaultSlowModeSeconds() | setDefaultSlowModeSeconds(String defaultSlowModeSeconds) |
| `GroupPermissions` | [`List<GroupPermission>`](../../doc/models/group-permission.md) | Required | - | List<GroupPermission> getGroupPermissions() | setGroupPermissions(List<GroupPermission> groupPermissions) |
| `EmailIn` | `String` | Required | - | String getEmailIn() | setEmailIn(String emailIn) |
| `EmailInAllowStrangers` | `boolean` | Required | - | boolean getEmailInAllowStrangers() | setEmailInAllowStrangers(boolean emailInAllowStrangers) |
| `MailinglistMirror` | `boolean` | Required | - | boolean getMailinglistMirror() | setMailinglistMirror(boolean mailinglistMirror) |
| `AllTopicsWiki` | `boolean` | Required | - | boolean getAllTopicsWiki() | setAllTopicsWiki(boolean allTopicsWiki) |
| `CanDelete` | `boolean` | Required | - | boolean getCanDelete() | setCanDelete(boolean canDelete) |
| `AllowBadges` | `boolean` | Required | - | boolean getAllowBadges() | setAllowBadges(boolean allowBadges) |
| `TopicFeaturedLinkAllowed` | `boolean` | Required | - | boolean getTopicFeaturedLinkAllowed() | setTopicFeaturedLinkAllowed(boolean topicFeaturedLinkAllowed) |
| `SearchPriority` | `int` | Required | - | int getSearchPriority() | setSearchPriority(int searchPriority) |
| `TopicPostingReviewGroupIds` | `List<Integer>` | Required | - | List<Integer> getTopicPostingReviewGroupIds() | setTopicPostingReviewGroupIds(List<Integer> topicPostingReviewGroupIds) |
| `ReplyPostingReviewGroupIds` | `List<Integer>` | Required | - | List<Integer> getReplyPostingReviewGroupIds() | setReplyPostingReviewGroupIds(List<Integer> replyPostingReviewGroupIds) |
| `UploadedLogo` | `String` | Required | - | String getUploadedLogo() | setUploadedLogo(String uploadedLogo) |
| `UploadedLogoDark` | `String` | Required | - | String getUploadedLogoDark() | setUploadedLogoDark(String uploadedLogoDark) |
| `UploadedBackground` | `String` | Required | - | String getUploadedBackground() | setUploadedBackground(String uploadedBackground) |
| `UploadedBackgroundDark` | `String` | Required | - | String getUploadedBackgroundDark() | setUploadedBackgroundDark(String uploadedBackgroundDark) |
| `CategoryTypes` | `Object` | Optional | - | Object getCategoryTypes() | setCategoryTypes(Object categoryTypes) |
| `CategoryTypeSettings` | `Object` | Optional | - | Object getCategoryTypeSettings() | setCategoryTypeSettings(Object categoryTypeSettings) |
| `AvailableCategoryTypes` | [`List<AvailableCategoryType>`](../../doc/models/available-category-type.md) | Optional | - | List<AvailableCategoryType> getAvailableCategoryTypes() | setAvailableCategoryTypes(List<AvailableCategoryType> availableCategoryTypes) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Category;
import com.example.discourse.models.GroupPermission;
import com.example.discourse.models.RequiredTagGroup;
import java.io.IOException;
import java.util.Arrays;

Category category = new Category.Builder(
    232,
    "name2",
    "color4",
    "text_color4",
    "style_type4",
    "emoji4",
    "icon6",
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
.locale("locale0")
.formTemplateIds(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.allowedTags(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.allowedTagGroups(Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ))
.allowGlobalTags(false)
.build();
```

