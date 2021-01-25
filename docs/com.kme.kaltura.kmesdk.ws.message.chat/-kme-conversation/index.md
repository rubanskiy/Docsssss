[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.chat](../index.md) / [KmeConversation](./index.md)

# KmeConversation

`data class KmeConversation : `[`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html)

### Types

| Name | Summary |
|---|---|
| [User](-user/index.md) | `data class User : `[`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeConversation(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, lastMessage: `[`KmeChatMessage`](../-kme-chat-message/index.md)`? = null, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, conversationType: `[`KmeConversationType`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-conversation-type/index.md)`? = null, isSystem: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null, avatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, unreadMessages: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`? = null, firstUser: `[`User`](-user/index.md)`? = null, secondUser: `[`User`](-user/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [avatar](avatar.md) | `val avatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [conversationType](conversation-type.md) | `val conversationType: `[`KmeConversationType`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-conversation-type/index.md)`?` |
| [firstUser](first-user.md) | `val firstUser: `[`User`](-user/index.md)`?` |
| [hasAccess](has-access.md) | `var hasAccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [id](id.md) | `val id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [isSystem](is-system.md) | `val isSystem: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [lastMessage](last-message.md) | `val lastMessage: `[`KmeChatMessage`](../-kme-chat-message/index.md)`?` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [secondUser](second-user.md) | `val secondUser: `[`User`](-user/index.md)`?` |
| [unreadMessages](unread-messages.md) | `val unreadMessages: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
