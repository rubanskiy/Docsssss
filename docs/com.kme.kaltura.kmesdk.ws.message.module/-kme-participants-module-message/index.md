[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../index.md) / [KmeParticipantsModuleMessage](./index.md)

# KmeParticipantsModuleMessage

`class KmeParticipantsModuleMessage<T : `[`ParticipantsPayload`](-participants-payload/index.md)`> : `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<`[`T`](index.md#T)`>`

### Types

| Name | Summary |
|---|---|
| [AllUsersHandPutPayload](-all-users-hand-put-payload/index.md) | `data class AllUsersHandPutPayload : `[`ParticipantsPayload`](-participants-payload/index.md) |
| [ChangeUserFocusEventPayload](-change-user-focus-event-payload/index.md) | `data class ChangeUserFocusEventPayload : `[`ParticipantsPayload`](-participants-payload/index.md) |
| [ParticipantsPayload](-participants-payload/index.md) | `class ParticipantsPayload : `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md) |
| [SetParticipantModerator](-set-participant-moderator/index.md) | `data class SetParticipantModerator : `[`ParticipantsPayload`](-participants-payload/index.md) |
| [UserMediaStateChangedPayload](-user-media-state-changed-payload/index.md) | `data class UserMediaStateChangedPayload : `[`ParticipantsPayload`](-participants-payload/index.md) |
| [UserMediaStateInitPayload](-user-media-state-init-payload/index.md) | `data class UserMediaStateInitPayload : `[`ParticipantsPayload`](-participants-payload/index.md) |
| [UserRaiseHandPayload](-user-raise-hand-payload/index.md) | `data class UserRaiseHandPayload : `[`ParticipantsPayload`](-participants-payload/index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeParticipantsModuleMessage()` |

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
