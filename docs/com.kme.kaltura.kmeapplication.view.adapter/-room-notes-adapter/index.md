[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.adapter](../index.md) / [RoomNotesAdapter](./index.md)

# RoomNotesAdapter

`class RoomNotesAdapter : Adapter<`[`RoomNotesHolder`](-room-notes-holder/index.md)`>`

### Types

| Name | Summary |
|---|---|
| [RoomNotesHolder](-room-notes-holder/index.md) | `inner class RoomNotesHolder : ViewHolder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomNotesAdapter()` |

### Properties

| Name | Summary |
|---|---|
| [onNoteActionsClick](on-note-actions-click.md) | `var onNoteActionsClick: (view: `[`View`](https://developer.android.com/reference/android/view/View.html)`, roomNote: KmeRoomNote) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onNoteClick](on-note-click.md) | `var onNoteClick: (view: `[`View`](https://developer.android.com/reference/android/view/View.html)`, roomNote: KmeRoomNote) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Functions

| Name | Summary |
|---|---|
| [getItemCount](get-item-count.md) | `fun getItemCount(): <ERROR CLASS>` |
| [onBindViewHolder](on-bind-view-holder.md) | `fun onBindViewHolder(holder: `[`RoomNotesHolder`](-room-notes-holder/index.md)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateViewHolder](on-create-view-holder.md) | `fun onCreateViewHolder(parent: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`, viewType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`RoomNotesHolder`](-room-notes-holder/index.md) |
| [setNotes](set-notes.md) | `fun setNotes(data: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeRoomNote>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
