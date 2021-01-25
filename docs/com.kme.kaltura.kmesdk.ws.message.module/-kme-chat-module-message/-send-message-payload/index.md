[kmeSdk](../../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../../index.md) / [KmeChatModuleMessage](../index.md) / [SendMessagePayload](./index.md)

# SendMessagePayload

`data class SendMessagePayload : `[`ChatPayload`](../-chat-payload/index.md)

### Types

| Name | Summary |
|---|---|
| [User](-user/index.md) | `data class User` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SendMessagePayload(conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, user: `[`User`](-user/index.md)`? = null, metadata: `[`KmeChatMessage`](../../../com.kme.kaltura.kmesdk.ws.message.chat/-kme-chat-message/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [companyId](company-id.md) | `var companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [conversationId](conversation-id.md) | `var conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [message](message.md) | `var message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [metadata](metadata.md) | `var metadata: `[`KmeChatMessage`](../../../com.kme.kaltura.kmesdk.ws.message.chat/-kme-chat-message/index.md)`?` |
| [roomId](room-id.md) | `var roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [user](user.md) | `var user: `[`User`](-user/index.md)`?` |
