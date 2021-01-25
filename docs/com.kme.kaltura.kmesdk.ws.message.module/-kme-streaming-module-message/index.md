[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../index.md) / [KmeStreamingModuleMessage](./index.md)

# KmeStreamingModuleMessage

`class KmeStreamingModuleMessage<T : `[`StreamingPayload`](-streaming-payload/index.md)`> : `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<`[`T`](index.md#T)`>`

### Types

| Name | Summary |
|---|---|
| [IceGatheringPublishDonePayload](-ice-gathering-publish-done-payload/index.md) | `data class IceGatheringPublishDonePayload : `[`StreamingPayload`](-streaming-payload/index.md) |
| [IceGatheringViewingDonePayload](-ice-gathering-viewing-done-payload/index.md) | `data class IceGatheringViewingDonePayload : `[`StreamingPayload`](-streaming-payload/index.md) |
| [SdpAnswerToFromViewer](-sdp-answer-to-from-viewer/index.md) | `data class SdpAnswerToFromViewer : `[`StreamingPayload`](-streaming-payload/index.md) |
| [SdpAnswerToPublisherPayload](-sdp-answer-to-publisher-payload/index.md) | `data class SdpAnswerToPublisherPayload : `[`StreamingPayload`](-streaming-payload/index.md) |
| [SdpOfferToViewerPayload](-sdp-offer-to-viewer-payload/index.md) | `data class SdpOfferToViewerPayload : `[`StreamingPayload`](-streaming-payload/index.md) |
| [StartPublishingPayload](-start-publishing-payload/index.md) | `data class StartPublishingPayload : `[`StreamingPayload`](-streaming-payload/index.md) |
| [StartViewingPayload](-start-viewing-payload/index.md) | `data class StartViewingPayload : `[`StreamingPayload`](-streaming-payload/index.md) |
| [StartedPublishPayload](-started-publish-payload/index.md) | `data class StartedPublishPayload : `[`StreamingPayload`](-streaming-payload/index.md) |
| [StreamingPayload](-streaming-payload/index.md) | `class StreamingPayload : `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md) |
| [UserDisconnectedPayload](-user-disconnected-payload/index.md) | `data class UserDisconnectedPayload : `[`StreamingPayload`](-streaming-payload/index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeStreamingModuleMessage()` |

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
