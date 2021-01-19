[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [ChatViewModel](./index.md)

# ChatViewModel

`class ChatViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ChatViewModel(kmeSdk: KME, timeUtil: `[`TimeUtil`](../../com.kme.kaltura.kmeapplication.util/-time-util/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [allowLoadMore](allow-load-more.md) | `var allowLoadMore: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [currentParticipant](current-participant.md) | `val currentParticipant: KmeParticipant?` |
| [deleteMessageLiveData](delete-message-live-data.md) | `val deleteMessageLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [messagesUpdatesLiveData](messages-updates-live-data.md) | `val messagesUpdatesLiveData: LiveData<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`>>` |
| [newMessageLiveData](new-message-live-data.md) | `val newMessageLiveData: LiveData<`[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`>` |
| [updateMessageLiveData](update-message-live-data.md) | `val updateMessageLiveData: LiveData<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`>>` |

### Functions

| Name | Summary |
|---|---|
| [buildSelfMessage](build-self-message.md) | `fun buildSelfMessage(conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`, replyMessage: `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`? = null): `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md) |
| [deleteMessage](delete-message.md) | `fun deleteMessage(messageId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getCurrentUserId](get-current-user-id.md) | `fun getCurrentUserId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getLastLoadedMessage](get-last-loaded-message.md) | `fun getLastLoadedMessage(): `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`?` |
| [loadMessages](load-messages.md) | `fun loadMessages(conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, fromMessageId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCleared](on-cleared.md) | `fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onConversationClosed](on-conversation-closed.md) | `fun onConversationClosed(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [send](send.md) | `fun send(conversationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`, replyMessage: `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [startPrivateChat](start-private-chat.md) | `fun startPrivateChat(targetUserId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [subscribe](subscribe.md) | `fun subscribe(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
