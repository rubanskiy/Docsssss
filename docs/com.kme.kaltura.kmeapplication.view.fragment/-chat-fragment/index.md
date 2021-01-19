[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.fragment](../index.md) / [ChatFragment](./index.md)

# ChatFragment

`class ChatFragment : `[`KmeFragment`](../-kme-fragment/index.md)`, OnLoadMoreListener, `[`OnChatContextMenuListener`](../../com.kme.kaltura.kmeapplication.view.adapter.viewholder/-on-chat-context-menu-listener/index.md)`, `[`IBottomSheetCallback`](../../com.kme.kaltura.kmeapplication.view/-i-bottom-sheet-callback/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ChatFragment()` |

### Functions

| Name | Summary |
|---|---|
| [getCurrentParticipant](get-current-participant.md) | `fun getCurrentParticipant(): KmeParticipant?` |
| [isParticipantJoined](is-participant-joined.md) | `fun isParticipantJoined(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onBottomSheetClosed](on-bottom-sheet-closed.md) | `fun onBottomSheetClosed(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onBottomSheetOpened](on-bottom-sheet-opened.md) | `fun onBottomSheetOpened(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `fun onCreateView(inflater: `[`LayoutInflater`](https://developer.android.com/reference/android/view/LayoutInflater.html)`, container: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`?, savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`View`](https://developer.android.com/reference/android/view/View.html)`?` |
| [onDelete](on-delete.md) | `fun onDelete(message: `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDestroyView](on-destroy-view.md) | `fun onDestroyView(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onLoadMore](on-load-more.md) | `fun onLoadMore(page: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, totalItemsCount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onReply](on-reply.md) | `fun onReply(message: `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`, replyAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onResume](on-resume.md) | `fun onResume(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStartPrivateChat](on-start-private-chat.md) | `fun onStartPrivateChat(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onViewCreated](on-view-created.md) | `fun onViewCreated(view: `[`View`](https://developer.android.com/reference/android/view/View.html)`, savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [hideHomeButton](../-kme-fragment/hide-home-button.md) | `fun hideHomeButton(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [showHomeButton](../-kme-fragment/show-home-button.md) | `fun showHomeButton(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toolbarTitle](../-kme-fragment/toolbar-title.md) | `fun toolbarTitle(title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [COMPANY_ID_ARG](-c-o-m-p-a-n-y_-i-d_-a-r-g.md) | `const val COMPANY_ID_ARG: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [CONVERSATION_ARG](-c-o-n-v-e-r-s-a-t-i-o-n_-a-r-g.md) | `const val CONVERSATION_ARG: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ROOM_ID_ARG](-r-o-o-m_-i-d_-a-r-g.md) | `const val ROOM_ID_ARG: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [newInstance](new-instance.md) | `fun newInstance(conversation: `[`MappedConversation`](../../com.kme.kaltura.kmeapplication.data/-mapped-conversation/index.md)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): <ERROR CLASS>` |
