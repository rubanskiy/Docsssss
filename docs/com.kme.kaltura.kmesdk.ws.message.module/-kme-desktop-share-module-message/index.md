[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../index.md) / [KmeDesktopShareModuleMessage](./index.md)

# KmeDesktopShareModuleMessage

`class KmeDesktopShareModuleMessage<T : `[`DesktopSharePayload`](-desktop-share-payload/index.md)`> : `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<`[`T`](index.md#T)`>`

### Types

| Name | Summary |
|---|---|
| [DesktopShareInitOnRoomInitPayload](-desktop-share-init-on-room-init-payload/index.md) | `data class DesktopShareInitOnRoomInitPayload : `[`DesktopSharePayload`](-desktop-share-payload/index.md) |
| [DesktopSharePayload](-desktop-share-payload/index.md) | `class DesktopSharePayload : `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md) |
| [DesktopShareQualityUpdatedPayload](-desktop-share-quality-updated-payload/index.md) | `data class DesktopShareQualityUpdatedPayload : `[`DesktopSharePayload`](-desktop-share-payload/index.md) |
| [DesktopShareStateUpdatedPayload](-desktop-share-state-updated-payload/index.md) | `data class DesktopShareStateUpdatedPayload : `[`DesktopSharePayload`](-desktop-share-payload/index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeDesktopShareModuleMessage()` |

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
