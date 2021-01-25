[kmeSdk](../../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../../index.md) / [KmeChatModuleMessage](../index.md) / [LoadMessagesPayload](./index.md)

# LoadMessagesPayload

`data class LoadMessagesPayload : `[`ChatPayload`](../-chat-payload/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LoadMessagesPayload(conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [companyId](company-id.md) | `var companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [conversationId](conversation-id.md) | `val conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [fromMessageId](from-message-id.md) | `var fromMessageId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [loadType](load-type.md) | `var loadType: `[`KmeLoadType`](../../../com.kme.kaltura.kmesdk.ws.message.type/-kme-load-type/index.md)`?` |
| [messages](messages.md) | `val messages: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`KmeChatMessage`](../../../com.kme.kaltura.kmesdk.ws.message.chat/-kme-chat-message/index.md)`>?` |
| [roomId](room-id.md) | `var roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
