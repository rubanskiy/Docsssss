[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.data](../index.md) / [MappedConversation](./index.md)

# MappedConversation

`class MappedConversation : IDialog<`[`MappedChatMessage`](../-mapped-chat-message/index.md)`>, `[`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MappedConversation(conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, conversationName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, avatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, participants: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MappedUser`](../-mapped-user/index.md)`>, lastChatMessage: `[`MappedChatMessage`](../-mapped-chat-message/index.md)`?, unreadCount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?, conversationType: KmeConversationType?, isSystem: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null, hasAccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [conversationType](conversation-type.md) | `val conversationType: KmeConversationType?` |
| [hasAccess](has-access.md) | `var hasAccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [isSystem](is-system.md) | `var isSystem: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [unreadCount](unread-count.md) | `var unreadCount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |

### Functions

| Name | Summary |
|---|---|
| [getDialogName](get-dialog-name.md) | `fun getDialogName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getDialogPhoto](get-dialog-photo.md) | `fun getDialogPhoto(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getId](get-id.md) | `fun getId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getLastMessage](get-last-message.md) | `fun getLastMessage(): `[`MappedChatMessage`](../-mapped-chat-message/index.md)`?` |
| [getUnreadCount](get-unread-count.md) | `fun getUnreadCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getUsers](get-users.md) | `fun getUsers(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<out IUser>?` |
| [setLastMessage](set-last-message.md) | `fun setLastMessage(message: `[`MappedChatMessage`](../-mapped-chat-message/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
