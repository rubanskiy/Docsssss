[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../index.md) / [KmeRoomRecordingMessage](./index.md)

# KmeRoomRecordingMessage

`class KmeRoomRecordingMessage<T : `[`RecordingPayload`](-recording-payload/index.md)`> : `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<`[`T`](index.md#T)`>`

### Types

| Name | Summary |
|---|---|
| [RecordingCompletedPayload](-recording-completed-payload/index.md) | `data class RecordingCompletedPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingConversionCompletedPayload](-recording-conversion-completed-payload/index.md) | `data class RecordingConversionCompletedPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingFailurePayload](-recording-failure-payload/index.md) | `data class RecordingFailurePayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingInitiatedPayload](-recording-initiated-payload/index.md) | `data class RecordingInitiatedPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingPayload](-recording-payload/index.md) | `class RecordingPayload : `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md) |
| [RecordingRxPayload](-recording-rx-payload/index.md) | `class RecordingRxPayload : `[`RecordingPayload`](-recording-payload/index.md) |
| [RecordingStartPayload](-recording-start-payload/index.md) | `data class RecordingStartPayload : `[`RecordingTxPayload`](-recording-tx-payload/index.md) |
| [RecordingStartedPayload](-recording-started-payload/index.md) | `data class RecordingStartedPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingStartingPayload](-recording-starting-payload/index.md) | `data class RecordingStartingPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingStatusPayload](-recording-status-payload/index.md) | `data class RecordingStatusPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingStopPayload](-recording-stop-payload/index.md) | `data class RecordingStopPayload : `[`RecordingTxPayload`](-recording-tx-payload/index.md) |
| [RecordingStoppedPayload](-recording-stopped-payload/index.md) | `data class RecordingStoppedPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |
| [RecordingTxPayload](-recording-tx-payload/index.md) | `class RecordingTxPayload : `[`RecordingPayload`](-recording-payload/index.md) |
| [RecordingUploadCompletedPayload](-recording-upload-completed-payload/index.md) | `data class RecordingUploadCompletedPayload : `[`RecordingRxPayload`](-recording-rx-payload/index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeRoomRecordingMessage()` |

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
