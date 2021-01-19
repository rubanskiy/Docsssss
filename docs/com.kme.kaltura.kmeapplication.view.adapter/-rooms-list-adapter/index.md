[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.adapter](../index.md) / [RoomsListAdapter](./index.md)

# RoomsListAdapter

`class RoomsListAdapter : Adapter<`[`RoomHolder`](-room-holder/index.md)`>`

### Types

| Name | Summary |
|---|---|
| [RoomHolder](-room-holder/index.md) | `inner class RoomHolder : ViewHolder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomsListAdapter()` |

### Properties

| Name | Summary |
|---|---|
| [onRoomClick](on-room-click.md) | `var onRoomClick: (room: KmeBaseRoom) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Functions

| Name | Summary |
|---|---|
| [addData](add-data.md) | `fun addData(data: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeBaseRoom>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getItemCount](get-item-count.md) | `fun getItemCount(): <ERROR CLASS>` |
| [onBindViewHolder](on-bind-view-holder.md) | `fun onBindViewHolder(holder: `[`RoomHolder`](-room-holder/index.md)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateViewHolder](on-create-view-holder.md) | `fun onCreateViewHolder(parent: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`, viewType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`RoomHolder`](-room-holder/index.md) |
