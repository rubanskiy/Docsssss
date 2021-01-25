[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../index.md) / [KmeChatModuleMessage](./index.md)

# KmeChatModuleMessage

`class KmeChatModuleMessage<T : `[`ChatPayload`](-chat-payload/index.md)`> : `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<`[`T`](index.md#T)`>`

### Types

| Name | Summary |
|---|---|
| [ChatPayload](-chat-payload/index.md) | `class ChatPayload : `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md) |
| [CreateDmConversationPayload](-create-dm-conversation-payload/index.md) | `data class CreateDmConversationPayload : `[`ChatPayload`](-chat-payload/index.md) |
| [CreatedDmConversationPayload](-created-dm-conversation-payload/index.md) | `data class CreatedDmConversationPayload : `[`ChatPayload`](-chat-payload/index.md) |
| [DeleteMessagePayload](-delete-message-payload/index.md) | `data class DeleteMessagePayload : `[`ChatPayload`](-chat-payload/index.md) |
| [GetConversationPayload](-get-conversation-payload/index.md) | `data class GetConversationPayload : `[`ChatPayload`](-chat-payload/index.md) |
| [GotConversationPayload](-got-conversation-payload/index.md) | `data class GotConversationPayload : `[`ChatPayload`](-chat-payload/index.md) |
| [LoadConversationPayload](-load-conversation-payload/index.md) | `data class LoadConversationPayload : `[`ChatPayload`](-chat-payload/index.md) |
| [LoadMessagesPayload](-load-messages-payload/index.md) | `data class LoadMessagesPayload : `[`ChatPayload`](-chat-payload/index.md) |
| [ReceiveConversationsPayload](-receive-conversations-payload/index.md) | `data class ReceiveConversationsPayload : `[`ChatPayload`](-chat-payload/index.md) |
| [ReceiveMessagePayload](-receive-message-payload/index.md) | `data class ReceiveMessagePayload : `[`ChatPayload`](-chat-payload/index.md) |
| [SendMessagePayload](-send-message-payload/index.md) | `data class SendMessagePayload : `[`ChatPayload`](-chat-payload/index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeChatModuleMessage()` |

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
