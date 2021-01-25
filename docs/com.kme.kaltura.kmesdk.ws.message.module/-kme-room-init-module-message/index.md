[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../index.md) / [KmeRoomInitModuleMessage](./index.md)

# KmeRoomInitModuleMessage

`class KmeRoomInitModuleMessage<T : `[`RoomInitPayload`](-room-init-payload/index.md)`> : `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<`[`T`](index.md#T)`>`

### Types

| Name | Summary |
|---|---|
| [AnyInstructorsIsConnectedToRoomPayload](-any-instructors-is-connected-to-room-payload/index.md) | `data class AnyInstructorsIsConnectedToRoomPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [ApprovalPayload](-approval-payload/index.md) | `data class ApprovalPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [CloseWebSocketPayload](-close-web-socket-payload/index.md) | `data class CloseWebSocketPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [InstructorIsOfflinePayload](-instructor-is-offline-payload/index.md) | `data class InstructorIsOfflinePayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [JoinRoomPayload](-join-room-payload/index.md) | `data class JoinRoomPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [JoinedRoomPayload](-joined-room-payload/index.md) | `data class JoinedRoomPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [NewUserJoinedPayload](-new-user-joined-payload/index.md) | `data class NewUserJoinedPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [RoomAvailableForParticipantPayload](-room-available-for-participant-payload/index.md) | `data class RoomAvailableForParticipantPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [RoomInitPayload](-room-init-payload/index.md) | `class RoomInitPayload : `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md) |
| [RoomParticipantLimitReachedPayload](-room-participant-limit-reached-payload/index.md) | `data class RoomParticipantLimitReachedPayload : `[`RoomInitPayload`](-room-init-payload/index.md) |
| [RoomStatePayload](-room-state-payload/index.md) | `data class RoomStatePayload : `[`RoomInitPayload`](-room-init-payload/index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeRoomInitModuleMessage()` |

### Inherited Properties

| Name | Summary |
|---|---|
| [constraint](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/constraint.md) | `var constraint: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`KmeConstraint`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-constraint/index.md)`>?` |
| [module](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/module.md) | `var module: `[`KmeMessageModule`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message-module/index.md)`?` |
| [name](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/name.md) | `var name: `[`KmeMessageEvent`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message-event/index.md)`?` |
| [payload](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/payload.md) | `var payload: `[`T`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md#T)`?` |
| [type](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/type.md) | `var type: `[`KmeMessageEventType`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message-event-type/index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [toType](../../com.kme.kaltura.kmesdk/to-type.md) | `fun <T> `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<*>.toType(): `[`T`](../../com.kme.kaltura.kmesdk/to-type.md#T)`?` |
