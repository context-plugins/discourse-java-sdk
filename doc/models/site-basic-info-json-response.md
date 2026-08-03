
# Site Basic Info Json Response

## Structure

`SiteBasicInfoJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `LogoUrl` | `String` | Required | - | String getLogoUrl() | setLogoUrl(String logoUrl) |
| `LogoSmallUrl` | `String` | Required | - | String getLogoSmallUrl() | setLogoSmallUrl(String logoSmallUrl) |
| `AppleTouchIconUrl` | `String` | Required | - | String getAppleTouchIconUrl() | setAppleTouchIconUrl(String appleTouchIconUrl) |
| `FaviconUrl` | `String` | Required | - | String getFaviconUrl() | setFaviconUrl(String faviconUrl) |
| `Title` | `String` | Required | - | String getTitle() | setTitle(String title) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `HeaderPrimaryColor` | `String` | Required | - | String getHeaderPrimaryColor() | setHeaderPrimaryColor(String headerPrimaryColor) |
| `HeaderBackgroundColor` | `String` | Required | - | String getHeaderBackgroundColor() | setHeaderBackgroundColor(String headerBackgroundColor) |
| `LoginRequired` | `boolean` | Required | - | boolean getLoginRequired() | setLoginRequired(boolean loginRequired) |
| `Locale` | `String` | Required | - | String getLocale() | setLocale(String locale) |
| `IncludeInDiscourseDiscover` | `boolean` | Required | - | boolean getIncludeInDiscourseDiscover() | setIncludeInDiscourseDiscover(boolean includeInDiscourseDiscover) |
| `MobileLogoUrl` | `String` | Required | - | String getMobileLogoUrl() | setMobileLogoUrl(String mobileLogoUrl) |

## Example

```java
import com.example.discourse.models.SiteBasicInfoJsonResponse;

SiteBasicInfoJsonResponse siteBasicInfoJsonResponse = new SiteBasicInfoJsonResponse.Builder(
    "logo_url4",
    "logo_small_url8",
    "apple_touch_icon_url2",
    "favicon_url6",
    "title2",
    "description6",
    "header_primary_color6",
    "header_background_color6",
    false,
    "locale4",
    false,
    "mobile_logo_url2"
)
.build();
```

