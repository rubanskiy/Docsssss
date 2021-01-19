[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.data](../index.md) / [MappedChatMessage](./index.md)

# MappedChatMessage

`class MappedChatMessage : IMessage, `[`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html)

### Types

| Name | Summary |
|---|---|
| [StyleType](-style-type/index.md) | `enum class StyleType` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MappedChatMessage(user: `[`MappedUser`](../-mapped-user/index.md)`, messageId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, createdAt: `[`Date`](https://developer.android.com/reference/java/util/Date.html)`, conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, status: `[`ChatMessageStatus`](../-chat-message-status/index.md)`? = null, replyMessage: `[`MappedChatMessage`](./index.md)`? = null, replyAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, styleType: `[`StyleType`](-style-type/index.md)` = StyleType.END_MESSAGE_STYLE)` |

### Properties

| Name | Summary |
|---|---|
| [conversationId](conversation-id.md) | `var conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [replyAll](reply-all.md) | `var replyAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [replyMessage](reply-message.md) | `var replyMessage: `[`MappedChatMessage`](./index.md)`?` |
| [status](status.md) | `var status: `[`ChatMessageStatus`](../-chat-message-status/index.md)`?` |
| [styleType](style-type.md) | `var styleType: `[`StyleType`](-style-type/index.md) |

### Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCreatedAt](get-created-at.md) | `fun getCreatedAt(): `[`Date`](https://developer.android.com/reference/java/util/Date.html) |
| [getId](get-id.md) | `fun getId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getText](get-text.md) | `fun getText(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getUser](get-user.md) | `fun getUser(): `[`MappedUser`](../-mapped-user/index.md) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
