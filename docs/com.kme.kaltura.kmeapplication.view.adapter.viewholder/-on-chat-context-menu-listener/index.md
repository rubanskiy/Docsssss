[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.adapter.viewholder](../index.md) / [OnChatContextMenuListener](./index.md)

# OnChatContextMenuListener

`interface OnChatContextMenuListener`

### Functions

| Name | Summary |
|---|---|
| [getCurrentParticipant](get-current-participant.md) | `abstract fun getCurrentParticipant(): KmeParticipant?` |
| [isParticipantJoined](is-participant-joined.md) | `abstract fun isParticipantJoined(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onDelete](on-delete.md) | `abstract fun onDelete(message: `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onReply](on-reply.md) | `abstract fun onReply(message: `[`MappedChatMessage`](../../com.kme.kaltura.kmeapplication.data/-mapped-chat-message/index.md)`, replyAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStartPrivateChat](on-start-private-chat.md) | `abstract fun onStartPrivateChat(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ChatFragment](../../com.kme.kaltura.kmeapplication.view.fragment/-chat-fragment/index.md) | `class ChatFragment : `[`KmeFragment`](../../com.kme.kaltura.kmeapplication.view.fragment/-kme-fragment/index.md)`, OnLoadMoreListener, `[`OnChatContextMenuListener`](./index.md)`, `[`IBottomSheetCallback`](../../com.kme.kaltura.kmeapplication.view/-i-bottom-sheet-callback/index.md) |
