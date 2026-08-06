
# Site Json Response

## Structure

`SiteJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `DefaultArchetype` | `String` | Required | - | String getDefaultArchetype() | setDefaultArchetype(String defaultArchetype) |
| `NotificationTypes` | [`NotificationTypes`](../../doc/models/notification-types.md) | Required | - | NotificationTypes getNotificationTypes() | setNotificationTypes(NotificationTypes notificationTypes) |
| `PostTypes` | [`PostTypes`](../../doc/models/post-types.md) | Required | - | PostTypes getPostTypes() | setPostTypes(PostTypes postTypes) |
| `TrustLevels` | [`TrustLevels`](../../doc/models/trust-levels.md) | Required | - | TrustLevels getTrustLevels() | setTrustLevels(TrustLevels trustLevels) |
| `UserTips` | [`UserTips`](../../doc/models/user-tips.md) | Optional | - | UserTips getUserTips() | setUserTips(UserTips userTips) |
| `Groups` | [`List<Group5>`](../../doc/models/group-5.md) | Required | - | List<Group5> getGroups() | setGroups(List<Group5> groups) |
| `Filters` | `List<Object>` | Required | - | List<Object> getFilters() | setFilters(List<Object> filters) |
| `HomepageChoices` | `List<Object>` | Required | - | List<Object> getHomepageChoices() | setHomepageChoices(List<Object> homepageChoices) |
| `Periods` | `List<Object>` | Required | - | List<Object> getPeriods() | setPeriods(List<Object> periods) |
| `TopMenuItems` | `List<Object>` | Required | - | List<Object> getTopMenuItems() | setTopMenuItems(List<Object> topMenuItems) |
| `AnonymousTopMenuItems` | `List<Object>` | Required | - | List<Object> getAnonymousTopMenuItems() | setAnonymousTopMenuItems(List<Object> anonymousTopMenuItems) |
| `UncategorizedCategoryId` | `int` | Required | - | int getUncategorizedCategoryId() | setUncategorizedCategoryId(int uncategorizedCategoryId) |
| `UserFieldMaxLength` | `int` | Required | - | int getUserFieldMaxLength() | setUserFieldMaxLength(int userFieldMaxLength) |
| `PostActionTypes` | [`List<PostActionType>`](../../doc/models/post-action-type.md) | Required | - | List<PostActionType> getPostActionTypes() | setPostActionTypes(List<PostActionType> postActionTypes) |
| `TopicFlagTypes` | [`List<TopicFlagType>`](../../doc/models/topic-flag-type.md) | Required | - | List<TopicFlagType> getTopicFlagTypes() | setTopicFlagTypes(List<TopicFlagType> topicFlagTypes) |
| `CanCreateTag` | `boolean` | Required | - | boolean getCanCreateTag() | setCanCreateTag(boolean canCreateTag) |
| `CanTagTopics` | `boolean` | Required | - | boolean getCanTagTopics() | setCanTagTopics(boolean canTagTopics) |
| `CanTagPms` | `boolean` | Required | - | boolean getCanTagPms() | setCanTagPms(boolean canTagPms) |
| `TagsFilterRegexp` | `String` | Required | - | String getTagsFilterRegexp() | setTagsFilterRegexp(String tagsFilterRegexp) |
| `TopTags` | [`List<TopTag>`](../../doc/models/top-tag.md) | Required | - | List<TopTag> getTopTags() | setTopTags(List<TopTag> topTags) |
| `WizardRequired` | `Boolean` | Optional | - | Boolean getWizardRequired() | setWizardRequired(Boolean wizardRequired) |
| `CanAssociateGroups` | `Boolean` | Optional | - | Boolean getCanAssociateGroups() | setCanAssociateGroups(Boolean canAssociateGroups) |
| `EmailConfigured` | `boolean` | Required | - | boolean getEmailConfigured() | setEmailConfigured(boolean emailConfigured) |
| `UpcomingChangesWithCss` | `List<String>` | Optional | - | List<String> getUpcomingChangesWithCss() | setUpcomingChangesWithCss(List<String> upcomingChangesWithCss) |
| `TopicFeaturedLinkAllowedCategoryIds` | `List<Object>` | Required | - | List<Object> getTopicFeaturedLinkAllowedCategoryIds() | setTopicFeaturedLinkAllowedCategoryIds(List<Object> topicFeaturedLinkAllowedCategoryIds) |
| `UserThemes` | [`List<UserTheme>`](../../doc/models/user-theme.md) | Required | - | List<UserTheme> getUserThemes() | setUserThemes(List<UserTheme> userThemes) |
| `UserColorSchemes` | [`List<UserColorScheme>`](../../doc/models/user-color-scheme.md) | Required | - | List<UserColorScheme> getUserColorSchemes() | setUserColorSchemes(List<UserColorScheme> userColorSchemes) |
| `DefaultLightColorScheme` | `Object` | Required | - | Object getDefaultLightColorScheme() | setDefaultLightColorScheme(Object defaultLightColorScheme) |
| `DefaultDarkColorScheme` | `Object` | Required | - | Object getDefaultDarkColorScheme() | setDefaultDarkColorScheme(Object defaultDarkColorScheme) |
| `CensoredRegexp` | `List<Object>` | Required | - | List<Object> getCensoredRegexp() | setCensoredRegexp(List<Object> censoredRegexp) |
| `CustomEmojiTranslation` | `Object` | Required | - | Object getCustomEmojiTranslation() | setCustomEmojiTranslation(Object customEmojiTranslation) |
| `WatchedWordsReplace` | `Object` | Required | - | Object getWatchedWordsReplace() | setWatchedWordsReplace(Object watchedWordsReplace) |
| `WatchedWordsLink` | `Object` | Required | - | Object getWatchedWordsLink() | setWatchedWordsLink(Object watchedWordsLink) |
| `MarkdownAdditionalOptions` | `Object` | Optional | - | Object getMarkdownAdditionalOptions() | setMarkdownAdditionalOptions(Object markdownAdditionalOptions) |
| `HashtagConfigurations` | `Object` | Optional | - | Object getHashtagConfigurations() | setHashtagConfigurations(Object hashtagConfigurations) |
| `HashtagIcons` | `Object` | Optional | - | Object getHashtagIcons() | setHashtagIcons(Object hashtagIcons) |
| `DisplayedAboutPluginStatGroups` | `List<Object>` | Optional | - | List<Object> getDisplayedAboutPluginStatGroups() | setDisplayedAboutPluginStatGroups(List<Object> displayedAboutPluginStatGroups) |
| `Categories` | [`List<Category4>`](../../doc/models/category-4.md) | Required | - | List<Category4> getCategories() | setCategories(List<Category4> categories) |
| `Archetypes` | [`List<Archetype>`](../../doc/models/archetype.md) | Required | - | List<Archetype> getArchetypes() | setArchetypes(List<Archetype> archetypes) |
| `UserFields` | `List<Object>` | Required | - | List<Object> getUserFields() | setUserFields(List<Object> userFields) |
| `AuthProviders` | `List<Object>` | Required | - | List<Object> getAuthProviders() | setAuthProviders(List<Object> authProviders) |
| `WhispersAllowedGroupsNames` | `List<Object>` | Optional | - | List<Object> getWhispersAllowedGroupsNames() | setWhispersAllowedGroupsNames(List<Object> whispersAllowedGroupsNames) |
| `DeniedEmojis` | `List<Object>` | Optional | - | List<Object> getDeniedEmojis() | setDeniedEmojis(List<Object> deniedEmojis) |
| `ValidFlagAppliesToTypes` | `List<Object>` | Optional | - | List<Object> getValidFlagAppliesToTypes() | setValidFlagAppliesToTypes(List<Object> validFlagAppliesToTypes) |
| `NavigationMenuSiteTopTags` | `List<Object>` | Optional | - | List<Object> getNavigationMenuSiteTopTags() | setNavigationMenuSiteTopTags(List<Object> navigationMenuSiteTopTags) |
| `FullNameRequiredForSignup` | `boolean` | Required | - | boolean getFullNameRequiredForSignup() | setFullNameRequiredForSignup(boolean fullNameRequiredForSignup) |
| `FullNameVisibleInSignup` | `boolean` | Required | - | boolean getFullNameVisibleInSignup() | setFullNameVisibleInSignup(boolean fullNameVisibleInSignup) |
| `AdminConfigLoginRoutes` | `List<Object>` | Optional | - | List<Object> getAdminConfigLoginRoutes() | setAdminConfigLoginRoutes(List<Object> adminConfigLoginRoutes) |
| `AccessControl` | [`AccessControl`](../../doc/models/access-control.md) | Optional | - | AccessControl getAccessControl() | setAccessControl(AccessControl accessControl) |
| `PermanentUpcomingChangeNames` | `List<String>` | Optional | - | List<String> getPermanentUpcomingChangeNames() | setPermanentUpcomingChangeNames(List<String> permanentUpcomingChangeNames) |
| `CategoryTypes` | [`List<CategoryType>`](../../doc/models/category-type.md) | Optional | - | List<CategoryType> getCategoryTypes() | setCategoryTypes(List<CategoryType> categoryTypes) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.Archetype;
import com.example.discourse.models.Category4;
import com.example.discourse.models.Group5;
import com.example.discourse.models.NotificationTypes;
import com.example.discourse.models.PostActionType;
import com.example.discourse.models.PostTypes;
import com.example.discourse.models.RequiredTagGroup;
import com.example.discourse.models.SiteJsonResponse;
import com.example.discourse.models.TopTag;
import com.example.discourse.models.TopicFlagType;
import com.example.discourse.models.TrustLevels;
import com.example.discourse.models.UserColorScheme;
import com.example.discourse.models.UserTheme;
import com.example.discourse.models.UserTips;
import java.io.IOException;
import java.util.Arrays;

SiteJsonResponse siteJsonResponse = new SiteJsonResponse.Builder(
    "default_archetype0",
    new NotificationTypes.Builder(
        10,
        148,
        16,
        82,
        92,
        206,
        86,
        52,
        254,
        26,
        192,
        214,
        110,
        200,
        104,
        70,
        72,
        92,
        128,
        110,
        94,
        8,
        90,
        54,
        38,
        230,
        190,
        170,
        38,
        142,
        90,
        52,
        182,
        62
    )
    .newFeatures(44)
    .adminProblems(196)
    .chatQuoted(4)
    .chatWatchedThread(54)
    .upcomingChangeAvailable(186)
    .build(),
    new PostTypes.Builder(
        174,
        126,
        86,
        152
    )
    .build(),
    new TrustLevels.Builder(
        196,
        160,
        18,
        28,
        70
    )
    .build(),
    Arrays.asList(
        new Group5.Builder(
            152,
            "name6",
            "flair_url6",
            "flair_bg_color0",
            "flair_color0",
            false
        )
        .fullName("full_name2")
        .displayName("display_name6")
        .build()
    ),
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
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    0,
    172,
    Arrays.asList(
        new PostActionType.Builder(
            90,
            "name_key2",
            "name8",
            "description8",
            "short_description4",
            false,
            false,
            false,
            Arrays.asList(
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
            ),
            false,
            false
        )
        .position(120)
        .system(false)
        .build()
    ),
    Arrays.asList(
        new TopicFlagType.Builder(
            12,
            "name_key8",
            "name4",
            "description4",
            "short_description0",
            false,
            false,
            false,
            Arrays.asList(
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
            ),
            false,
            false
        )
        .position(42)
        .system(false)
        .build()
    ),
    false,
    false,
    false,
    "tags_filter_regexp6",
    Arrays.asList(
        new TopTag.Builder(
            22,
            "name8",
            "slug2"
        )
        .additionalProperty("exampleAdditionalProperty", ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
        .build()
    ),
    false,
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        new UserTheme.Builder(
            108,
            "name6",
            false,
            124
        )
        .darkColorSchemeId(240)
        .onlyThemeColorSchemes(false)
        .build()
    ),
    Arrays.asList(
        new UserColorScheme.Builder(
            24,
            "name8",
            false,
            Arrays.asList(
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
            )
        )
        .themeId(250)
        .build()
    ),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
    Arrays.asList(
        new Category4.Builder(
            16,
            "name8",
            "color2",
            "text_color0",
            "slug2",
            172,
            244,
            46,
            "topic_url0",
            false,
            54,
            112,
            "topic_template6",
            "topic_title_placeholder4",
            false,
            74,
            "sort_order8",
            false,
            false,
            140,
            "default_view2",
            "subcategory_list_style4",
            "default_top_period2",
            "default_list_filter6",
            172,
            false,
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
        .build()
    ),
    Arrays.asList(
        new Archetype.Builder(
            "id8",
            "name8",
            Arrays.asList(
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
            )
        )
        .build()
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    false,
    false
)
.userTips(new UserTips.Builder(
        66,
        210,
        220,
        254,
        202
    )
    .build())
.wizardRequired(false)
.canAssociateGroups(false)
.upcomingChangesWithCss(Arrays.asList(
        "upcoming_changes_with_css1",
        "upcoming_changes_with_css2",
        "upcoming_changes_with_css3"
    ))
.markdownAdditionalOptions(ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"))
.build();
```

