
# Client Class Documentation

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| defaultHost | `String` | *Default*: `"discourse.example.com"` |
| environment | [`Environment`](../README.md#environments) | The API environment. <br> **Default: `Environment.PRODUCTION`** |
| httpClientConfig | [`Consumer<HttpClientConfiguration.Builder>`](../doc/http-client-configuration-builder.md) | Set up Http Client Configuration instance. |
| loggingConfig | [`Consumer<ApiLoggingConfiguration.Builder>`](../doc/api-logging-configuration-builder.md) | Set up Logging Configuration instance. |

The API client can be initialized as follows:

```java
import com.example.discourse.DiscourseApiDocumentationClient;
import com.example.discourse.Environment;
import com.example.discourse.exceptions.ApiException;
import com.example.discourse.http.response.ApiResponse;
import org.slf4j.event.Level;

public class Program {
    public static void main(String[] args) {
        DiscourseApiDocumentationClient client = new DiscourseApiDocumentationClient.Builder()
            .loggingConfig(builder -> builder
                    .level(Level.DEBUG)
                    .requestConfig(logConfigBuilder -> logConfigBuilder.body(true))
                    .responseConfig(logConfigBuilder -> logConfigBuilder.headers(true)))
            .httpClientConfig(configBuilder -> configBuilder
                    .timeout(0))
            .environment(Environment.PRODUCTION)
            .defaultHost("discourse.example.com")
            .build();

    }
}
```

## Discourse API DocumentationClient Class

The gateway for the SDK. This class acts as a factory for the Apis and also holds the configuration of the SDK.

### Apis

| Name | Description | Return Type |
|  --- | --- | --- |
| `getDiscourseCalendarEventsApi()` | Provides access to DiscourseCalendarEvents controller. | `DiscourseCalendarEventsApi` |
| `getBackupsApi()` | Provides access to Backups controller. | `BackupsApi` |
| `getBadgesApi()` | Provides access to Badges controller. | `BadgesApi` |
| `getCategoriesApi()` | Provides access to Categories controller. | `CategoriesApi` |
| `getGroupsApi()` | Provides access to Groups controller. | `GroupsApi` |
| `getInvitesApi()` | Provides access to Invites controller. | `InvitesApi` |
| `getNotificationsApi()` | Provides access to Notifications controller. | `NotificationsApi` |
| `getPostsApi()` | Provides access to Posts controller. | `PostsApi` |
| `getPrivateMessagesApi()` | Provides access to PrivateMessages controller. | `PrivateMessagesApi` |
| `getSearchApi()` | Provides access to Search controller. | `SearchApi` |
| `getSiteApi()` | Provides access to Site controller. | `SiteApi` |
| `getTagsApi()` | Provides access to Tags controller. | `TagsApi` |
| `getTopicsApi()` | Provides access to Topics controller. | `TopicsApi` |
| `getUploadsApi()` | Provides access to Uploads controller. | `UploadsApi` |
| `getUsersApi()` | Provides access to Users controller. | `UsersApi` |

### Methods

| Name | Description | Return Type |
|  --- | --- | --- |
| `shutdown()` | Shutdown the underlying HttpClient instance. | `void` |
| `getEnvironment()` | Current API environment. | `Environment` |
| `getDefaultHost()` | defaultHost value. | `String` |
| `getHttpClient()` | The HTTP Client instance to use for making HTTP requests. | `HttpClient` |
| `getHttpClientConfig()` | Http Client Configuration instance. | [`ReadonlyHttpClientConfiguration`](../doc/http-client-configuration.md) |
| `getLoggingConfig()` | Logging Configuration instance. | [`ReadonlyLoggingConfiguration`](../doc/api-logging-configuration.md) |
| `getBaseUri(Server server)` | Get base URI by current environment | `String` |
| `getBaseUri()` | Get base URI by current environment | `String` |

