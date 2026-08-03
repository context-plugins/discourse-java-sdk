
# U Json Response

## Structure

`UJsonResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `UserBadges` | `List<Object>` | Required | - | List<Object> getUserBadges() | setUserBadges(List<Object> userBadges) |
| `User` | [`User8`](../../doc/models/user-8.md) | Required | - | User8 getUser() | setUser(User8 user) |

## Example

```java
import com.example.discourse.ApiHelper;
import com.example.discourse.models.CustomFields;
import com.example.discourse.models.FeaturedTopic;
import com.example.discourse.models.Group7;
import com.example.discourse.models.GroupUser;
import com.example.discourse.models.UJsonResponse;
import com.example.discourse.models.User8;
import com.example.discourse.models.UserAuthToken;
import com.example.discourse.models.UserNotificationSchedule;
import com.example.discourse.models.UserOption;
import java.io.IOException;
import java.util.Arrays;
import java.util.LinkedHashMap;

UJsonResponse uJsonResponse = new UJsonResponse.Builder(
    Arrays.asList(
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
        ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
    ),
    new User8.Builder(
        76,
        "username0",
        "name0",
        "avatar_template0",
        "last_posted_at8",
        "last_seen_at6",
        "created_at2",
        false,
        false,
        false,
        false,
        false,
        false,
        196,
        false,
        false,
        "title4",
        158,
        new CustomFields.Builder()
            .firstName("first_name2")
            .build(),
        24,
        170,
        88,
        "primary_group_name8",
        126,
        "flair_name6",
        "flair_url0",
        "flair_bg_color4",
        "flair_color6",
        new FeaturedTopic.Builder(
            50,
            "title6",
            "fancy_title0",
            "slug6",
            188
        )
        .build(),
        false,
        false,
        false,
        false,
        false,
        152,
        false,
        4,
        24,
        false,
        false,
        false,
        48,
        232,
        false,
        false,
        "locale8",
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
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
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
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
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        "system_avatar_upload_id2",
        "system_avatar_template6",
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        94,
        false,
        false,
        false,
        false,
        "user_api_keys4",
        Arrays.asList(
            new UserAuthToken.Builder(
                30,
                "client_ip2",
                "location6",
                "browser2",
                "device8",
                "os0",
                "icon4",
                "created_at0",
                "seen_at2",
                false
            )
            .build()
        ),
        new UserNotificationSchedule.Builder(
            false,
            242,
            54,
            130,
            246,
            112,
            212,
            160,
            110,
            186,
            212,
            48,
            64,
            102,
            208
        )
        .build(),
        false,
        Arrays.asList(
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
            ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
        ),
        "invited_by4",
        Arrays.asList(
            new Group7.Builder(
                152,
                false,
                "name6",
                "display_name6",
                248,
                236,
                92,
                196,
                false,
                "title2",
                "grant_trust_level8",
                "incoming_email6",
                false,
                "flair_url6",
                "flair_bg_color0",
                "flair_color0",
                "bio_raw8",
                "bio_cooked2",
                "bio_excerpt0",
                false,
                false,
                false,
                "full_name2",
                112,
                "membership_request_template2",
                0,
                false,
                false,
                false
            )
            .build()
        ),
        Arrays.asList(
            new GroupUser.Builder(
                176,
                4,
                4
            )
            .owner(false)
            .build()
        ),
        new UserOption.Builder(
            122,
            false,
            176,
            false,
            112,
            58,
            false,
            "color_scheme_id2",
            "dark_scheme_id6",
            false,
            false,
            false,
            false,
            false,
            8,
            false,
            128,
            80,
            210,
            154,
            false,
            64,
            false,
            "push_notification_level4",
            false,
            false,
            Arrays.asList(
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}"),
                ApiHelper.deserialize("{\"key1\":\"val1\",\"key2\":\"val2\"}")
            ),
            74,
            false,
            false,
            "homepage_id4",
            false,
            false,
            false,
            "text_size4",
            126,
            "title_count_mode4",
            "timezone2",
            false,
            false,
            78,
            false
        )
        .bookmarkAutoDeletePreference(190)
        .defaultCalendar("default_calendar2")
        .oldestSearchLogDate("oldest_search_log_date2")
        .sidebarLinkToFilteredList(false)
        .sidebarShowCountOfNewItems(false)
        .build()
    )
    .canIgnoreUsers(false)
    .canMuteUsers(false)
    .secondFactorBackupEnabled(false)
    .userFields(new LinkedHashMap<String, String>() {{
            put("key0", "user_fields1");
            put("key1", "user_fields0");
            put("key2", "user_fields9");
        }})
    .pendingPostsCount(124)
    .build()
)
.build();
```

