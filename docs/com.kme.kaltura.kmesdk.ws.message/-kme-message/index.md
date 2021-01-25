[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message](../index.md) / [KmeMessage](./index.md)

# KmeMessage

`open class KmeMessage<T : `[`Payload`](-payload/index.md)`>`

### Types

| Name | Summary |
|---|---|
| [Payload](-payload/index.md) | `open class Payload` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeMessage()` |

### Properties

| Name | Summary |
|---|---|
| [constraint](constraint.md) | `var constraint: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`KmeConstraint`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-constraint/index.md)`>?` |
| [module](module.md) | `var module: `[`KmeMessageModule`](../-kme-message-module/index.md)`?` |
| [name](name.md) | `var name: `[`KmeMessageEvent`](../-kme-message-event/index.md)`?` |
| [payload](payload.md) | `var payload: `[`T`](index.md#T)`?` |
| [type](type.md) | `var type: `[`KmeMessageEventType`](../-kme-message-event-type/index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [toType](../../com.kme.kaltura.kmesdk/to-type.md) | `fun <T> `[`KmeMessage`](./index.md)`<*>.toType(): `[`T`](../../com.kme.kaltura.kmesdk/to-type.md#T)`?` |

### Inheritors

| Name | Summary |
|---|---|
| [KmeActiveContentModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-active-content-module-message/index.md) | `class KmeActiveContentModuleMessage<T : `[`ActiveContentPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-active-content-module-message/-active-content-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-active-content-module-message/index.md#T)`>` |
| [KmeBannersModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-banners-module-message/index.md) | `class KmeBannersModuleMessage<T : `[`BannersPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-banners-module-message/-banners-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-banners-module-message/index.md#T)`>` |
| [KmeChatModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-chat-module-message/index.md) | `class KmeChatModuleMessage<T : `[`ChatPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-chat-module-message/-chat-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-chat-module-message/index.md#T)`>` |
| [KmeDesktopShareModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-desktop-share-module-message/index.md) | `class KmeDesktopShareModuleMessage<T : `[`DesktopSharePayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-desktop-share-module-message/-desktop-share-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-desktop-share-module-message/index.md#T)`>` |
| [KmeParticipantsModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-participants-module-message/index.md) | `class KmeParticipantsModuleMessage<T : `[`ParticipantsPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-participants-module-message/-participants-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-participants-module-message/index.md#T)`>` |
| [KmeRoomInitModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-init-module-message/index.md) | `class KmeRoomInitModuleMessage<T : `[`RoomInitPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-init-module-message/-room-init-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-init-module-message/index.md#T)`>` |
| [KmeRoomNotesMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-notes-message/index.md) | `class KmeRoomNotesMessage<T : `[`NotesPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-notes-message/-notes-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-notes-message/index.md#T)`>` |
| [KmeRoomRecordingMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-recording-message/index.md) | `class KmeRoomRecordingMessage<T : `[`RecordingPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-recording-message/-recording-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-recording-message/index.md#T)`>` |
| [KmeRoomSettingsModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-settings-module-message/index.md) | `class KmeRoomSettingsModuleMessage<T : `[`SettingsPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-settings-module-message/-settings-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-room-settings-module-message/index.md#T)`>` |
| [KmeSlidesPlayerModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-slides-player-module-message/index.md) | `class KmeSlidesPlayerModuleMessage<T : `[`SlidePlayerPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-slides-player-module-message/-slide-player-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-slides-player-module-message/index.md#T)`>` |
| [KmeStreamingModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-streaming-module-message/index.md) | `class KmeStreamingModuleMessage<T : `[`StreamingPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-streaming-module-message/-streaming-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-streaming-module-message/index.md#T)`>` |
| [KmeVideoModuleMessage](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-video-module-message/index.md) | `class KmeVideoModuleMessage<T : `[`VideoPayload`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-video-module-message/-video-payload/index.md)`> : `[`KmeMessage`](./index.md)`<`[`T`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-video-module-message/index.md#T)`>` |
