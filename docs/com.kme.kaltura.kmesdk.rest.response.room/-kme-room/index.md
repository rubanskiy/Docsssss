[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.response.room](../index.md) / [KmeRoom](./index.md)

# KmeRoom

`data class KmeRoom : `[`KmeBaseRoom`](../-kme-base-room/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeRoom(settings: `[`KmeSettings`](../../com.kme.kaltura.kmesdk.rest.response.room.settings/-kme-settings/index.md)`?, settingsV2: `[`KmeSettingsV2`](../../com.kme.kaltura.kmesdk.rest.response.room.settings/-kme-settings-v2/index.md)`?)` |

### Properties

| Name | Summary |
|---|---|
| [settings](settings.md) | `val settings: `[`KmeSettings`](../../com.kme.kaltura.kmesdk.rest.response.room.settings/-kme-settings/index.md)`?` |
| [settingsV2](settings-v2.md) | `val settingsV2: `[`KmeSettingsV2`](../../com.kme.kaltura.kmesdk.rest.response.room.settings/-kme-settings-v2/index.md)`?` |

### Inherited Properties

| Name | Summary |
|---|---|
| [activeBreakoutId](../-kme-base-room/active-breakout-id.md) | `val activeBreakoutId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [additionalData](../-kme-base-room/additional-data.md) | `val additionalData: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [alias](../-kme-base-room/alias.md) | `val alias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [allowGuestEnterLiveClass](../-kme-base-room/allow-guest-enter-live-class.md) | `val allowGuestEnterLiveClass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [allowGuestEnterSelfPaced](../-kme-base-room/allow-guest-enter-self-paced.md) | `val allowGuestEnterSelfPaced: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [appVersion](../-kme-base-room/app-version.md) | `val appVersion: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [autoUploadRecordings](../-kme-base-room/auto-upload-recordings.md) | `val autoUploadRecordings: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [avatar](../-kme-base-room/avatar.md) | `var avatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [chatMigrateStatus](../-kme-base-room/chat-migrate-status.md) | `val chatMigrateStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [companyAvatar](../-kme-base-room/company-avatar.md) | `val companyAvatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [companyData](../-kme-base-room/company-data.md) | `val companyData: `[`CompanyData`](../-kme-base-room/-company-data/index.md)`?` |
| [companyId](../-kme-base-room/company-id.md) | `val companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [companyName](../-kme-base-room/company-name.md) | `val companyName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [conferenceId](../-kme-base-room/conference-id.md) | `val conferenceId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [conferenceTokenUrl](../-kme-base-room/conference-token-url.md) | `val conferenceTokenUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [dateCreated](../-kme-base-room/date-created.md) | `val dateCreated: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [dateModified](../-kme-base-room/date-modified.md) | `val dateModified: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [defaultPlaylistId](../-kme-base-room/default-playlist-id.md) | `val defaultPlaylistId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [deleted](../-kme-base-room/deleted.md) | `val deleted: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [description](../-kme-base-room/description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [duration](../-kme-base-room/duration.md) | `val duration: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [fileHierarchyId](../-kme-base-room/file-hierarchy-id.md) | `val fileHierarchyId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [id](../-kme-base-room/id.md) | `val id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [indexId](../-kme-base-room/index-id.md) | `val indexId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [instructors](../-kme-base-room/instructors.md) | `val instructors: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Instructor`](../-kme-base-room/-instructor/index.md)`>?` |
| [isOnDemand](../-kme-base-room/is-on-demand.md) | `val isOnDemand: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [isTurnConfigured](../-kme-base-room/is-turn-configured.md) | `val isTurnConfigured: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [isUserModerator](../-kme-base-room/is-user-moderator.md) | `val isUserModerator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [licenseId](../-kme-base-room/license-id.md) | `val licenseId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [ltiRoomId](../-kme-base-room/lti-room-id.md) | `val ltiRoomId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [maxGuests](../-kme-base-room/max-guests.md) | `val maxGuests: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [migrateLog](../-kme-base-room/migrate-log.md) | `val migrateLog: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [name](../-kme-base-room/name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [parentRoomId](../-kme-base-room/parent-room-id.md) | `val parentRoomId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [playlistId](../-kme-base-room/playlist-id.md) | `val playlistId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [playlistMigrateStatus](../-kme-base-room/playlist-migrate-status.md) | `val playlistMigrateStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [privacyLevel](../-kme-base-room/privacy-level.md) | `val privacyLevel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [recordingHours](../-kme-base-room/recording-hours.md) | `val recordingHours: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [roomUserRole](../-kme-base-room/room-user-role.md) | `val roomUserRole: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [serverId](../-kme-base-room/server-id.md) | `val serverId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [showJoinLiveClass](../-kme-base-room/show-join-live-class.md) | `val showJoinLiveClass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [status](../-kme-base-room/status.md) | `val status: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [streamingHours](../-kme-base-room/streaming-hours.md) | `val streamingHours: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [summary](../-kme-base-room/summary.md) | `val summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [type](../-kme-base-room/type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [userCreated](../-kme-base-room/user-created.md) | `val userCreated: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [userModified](../-kme-base-room/user-modified.md) | `val userModified: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [userRole](../-kme-base-room/user-role.md) | `val userRole: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [viewingHours](../-kme-base-room/viewing-hours.md) | `val viewingHours: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [whiteboardMigrateStatus](../-kme-base-room/whiteboard-migrate-status.md) | `val whiteboardMigrateStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
