[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.chat](../index.md) / [KmeChatMessage](./index.md)

# KmeChatMessage

`data class KmeChatMessage : `[`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html)

### Types

| Name | Summary |
|---|---|
| [Metadata](-metadata/index.md) | `data class Metadata : `[`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeChatMessage(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, metadata: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, timestamp: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, user: `[`KmeUserInfoData`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-user-info-data/index.md)`? = null, replyAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null, parsedMetadata: `[`Metadata`](-metadata/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [conversationId](conversation-id.md) | `val conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [id](id.md) | `var id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [message](message.md) | `var message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [metadata](metadata.md) | `val metadata: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [parsedMetadata](parsed-metadata.md) | `var parsedMetadata: `[`Metadata`](-metadata/index.md)`?` |
| [replyAll](reply-all.md) | `var replyAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [timestamp](timestamp.md) | `val timestamp: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [user](user.md) | `var user: `[`KmeUserInfoData`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-user-info-data/index.md)`?` |
