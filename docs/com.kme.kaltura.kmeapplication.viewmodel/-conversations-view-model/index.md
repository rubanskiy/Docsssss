[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [ConversationsViewModel](./index.md)

# ConversationsViewModel

`class ConversationsViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConversationsViewModel(kmeSdk: KME, timeUtil: `[`TimeUtil`](../../com.kme.kaltura.kmeapplication.util/-time-util/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [allUnreadMessageCounterLiveData](all-unread-message-counter-live-data.md) | `val allUnreadMessageCounterLiveData: LiveData<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [closeConversationLiveData](close-conversation-live-data.md) | `val closeConversationLiveData: LiveData<`[`MappedConversation`](../../com.kme.kaltura.kmeapplication.data/-mapped-conversation/index.md)`?>` |
| [conversationChangedLiveData](conversation-changed-live-data.md) | `val conversationChangedLiveData: LiveData<`[`MappedConversation`](../../com.kme.kaltura.kmeapplication.data/-mapped-conversation/index.md)`>` |
| [conversationsLiveData](conversations-live-data.md) | `val conversationsLiveData: LiveData<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MappedConversation`](../../com.kme.kaltura.kmeapplication.data/-mapped-conversation/index.md)`>>` |
| [openConversationLiveData](open-conversation-live-data.md) | `val openConversationLiveData: LiveData<`[`MappedConversation`](../../com.kme.kaltura.kmeapplication.data/-mapped-conversation/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [filter](filter.md) | `fun filter(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [loadConversations](load-conversations.md) | `fun loadConversations(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onChatSettingsChanged](on-chat-settings-changed.md) | `fun onChatSettingsChanged(settings: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<KmePermissionKey?, KmePermissionValue?>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCleared](on-cleared.md) | `fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onNewMessage](on-new-message.md) | `fun onNewMessage(message: `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`?, increaseCount: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [openConversation](open-conversation.md) | `fun openConversation(conversation: `[`MappedConversation`](../../com.kme.kaltura.kmeapplication.data/-mapped-conversation/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOpenedConversation](set-opened-conversation.md) | `fun setOpenedConversation(conversation: `[`MappedConversation`](../../com.kme.kaltura.kmeapplication.data/-mapped-conversation/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
