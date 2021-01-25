[kmeSdk](../../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../../index.md) / [KmeChatModuleMessage](../index.md) / [ReceiveMessagePayload](./index.md)

# ReceiveMessagePayload

`data class ReceiveMessagePayload : `[`ChatPayload`](../-chat-payload/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ReceiveMessagePayload(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, metadata: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, timestamp: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, user: `[`KmeUserInfoData`](../../../com.kme.kaltura.kmesdk.rest.response.user/-kme-user-info-data/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [conversationId](conversation-id.md) | `val conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [id](id.md) | `val id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [message](message.md) | `val message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [metadata](metadata.md) | `val metadata: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [parsedMetadata](parsed-metadata.md) | `var parsedMetadata: `[`Metadata`](../../../com.kme.kaltura.kmesdk.ws.message.chat/-kme-chat-message/-metadata/index.md)`?` |
| [timestamp](timestamp.md) | `val timestamp: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [user](user.md) | `val user: `[`KmeUserInfoData`](../../../com.kme.kaltura.kmesdk.rest.response.user/-kme-user-info-data/index.md)`?` |
