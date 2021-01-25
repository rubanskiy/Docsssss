[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.response.room](../index.md) / [KmeBaseRoom](./index.md)

# KmeBaseRoom

`open class KmeBaseRoom : `[`KmeResponseData`](../../com.kme.kaltura.kmesdk.rest.response/-kme-response-data/index.md)

### Types

| Name | Summary |
|---|---|
| [CompanyData](-company-data/index.md) | `data class CompanyData` |
| [Instructor](-instructor/index.md) | `data class Instructor` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeBaseRoom()` |

### Properties

| Name | Summary |
|---|---|
| [activeBreakoutId](active-breakout-id.md) | `val activeBreakoutId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [additionalData](additional-data.md) | `val additionalData: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [alias](alias.md) | `val alias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [allowGuestEnterLiveClass](allow-guest-enter-live-class.md) | `val allowGuestEnterLiveClass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [allowGuestEnterSelfPaced](allow-guest-enter-self-paced.md) | `val allowGuestEnterSelfPaced: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [appVersion](app-version.md) | `val appVersion: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [autoUploadRecordings](auto-upload-recordings.md) | `val autoUploadRecordings: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [avatar](avatar.md) | `var avatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [chatMigrateStatus](chat-migrate-status.md) | `val chatMigrateStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [companyAvatar](company-avatar.md) | `val companyAvatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [companyData](company-data.md) | `val companyData: `[`CompanyData`](-company-data/index.md)`?` |
| [companyId](company-id.md) | `val companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [companyName](company-name.md) | `val companyName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [conferenceId](conference-id.md) | `val conferenceId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [conferenceTokenUrl](conference-token-url.md) | `val conferenceTokenUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [dateCreated](date-created.md) | `val dateCreated: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [dateModified](date-modified.md) | `val dateModified: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [defaultPlaylistId](default-playlist-id.md) | `val defaultPlaylistId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [deleted](deleted.md) | `val deleted: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [duration](duration.md) | `val duration: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [fileHierarchyId](file-hierarchy-id.md) | `val fileHierarchyId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [id](id.md) | `val id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [indexId](index-id.md) | `val indexId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [instructors](instructors.md) | `val instructors: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Instructor`](-instructor/index.md)`>?` |
| [isOnDemand](is-on-demand.md) | `val isOnDemand: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [isTurnConfigured](is-turn-configured.md) | `val isTurnConfigured: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [isUserModerator](is-user-moderator.md) | `val isUserModerator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [licenseId](license-id.md) | `val licenseId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [ltiRoomId](lti-room-id.md) | `val ltiRoomId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [maxGuests](max-guests.md) | `val maxGuests: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [migrateLog](migrate-log.md) | `val migrateLog: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [parentRoomId](parent-room-id.md) | `val parentRoomId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [playlistId](playlist-id.md) | `val playlistId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [playlistMigrateStatus](playlist-migrate-status.md) | `val playlistMigrateStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [privacyLevel](privacy-level.md) | `val privacyLevel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [recordingHours](recording-hours.md) | `val recordingHours: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [roomUserRole](room-user-role.md) | `val roomUserRole: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [serverId](server-id.md) | `val serverId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [showJoinLiveClass](show-join-live-class.md) | `val showJoinLiveClass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [status](status.md) | `val status: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [streamingHours](streaming-hours.md) | `val streamingHours: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [summary](summary.md) | `val summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [type](type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [userCreated](user-created.md) | `val userCreated: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [userModified](user-modified.md) | `val userModified: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [userRole](user-role.md) | `val userRole: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [viewingHours](viewing-hours.md) | `val viewingHours: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [whiteboardMigrateStatus](whiteboard-migrate-status.md) | `val whiteboardMigrateStatus: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |

### Inherited Properties

| Name | Summary |
|---|---|
| [code](../../com.kme.kaltura.kmesdk.rest.response/-kme-response-data/code.md) | `val code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [message](../../com.kme.kaltura.kmesdk.rest.response/-kme-response-data/message.md) | `val message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |

### Inheritors

| Name | Summary |
|---|---|
| [KmeRoom](../-kme-room/index.md) | `data class KmeRoom : `[`KmeBaseRoom`](./index.md) |
