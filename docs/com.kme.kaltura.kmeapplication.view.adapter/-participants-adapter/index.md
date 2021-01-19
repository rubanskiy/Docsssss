[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.adapter](../index.md) / [ParticipantsAdapter](./index.md)

# ParticipantsAdapter

`class ParticipantsAdapter : Adapter<`[`ParticipantHolder`](-participant-holder/index.md)`>, `[`Filterable`](https://developer.android.com/reference/android/widget/Filterable.html)

### Types

| Name | Summary |
|---|---|
| [ParticipantHolder](-participant-holder/index.md) | `inner class ParticipantHolder : ViewHolder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ParticipantsAdapter()` |

### Properties

| Name | Summary |
|---|---|
| [onParticipantClick](on-participant-click.md) | `var onParticipantClick: (view: `[`View`](https://developer.android.com/reference/android/view/View.html)`, participant: KmeParticipant) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Functions

| Name | Summary |
|---|---|
| [addOrUpdateParticipant](add-or-update-participant.md) | `fun addOrUpdateParticipant(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getFilter](get-filter.md) | `fun getFilter(): `[`Filter`](https://developer.android.com/reference/android/widget/Filter.html) |
| [getItemCount](get-item-count.md) | `fun getItemCount(): <ERROR CLASS>` |
| [onBindViewHolder](on-bind-view-holder.md) | `fun onBindViewHolder(holder: `[`ParticipantHolder`](-participant-holder/index.md)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateViewHolder](on-create-view-holder.md) | `fun onCreateViewHolder(parent: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`, viewType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`ParticipantHolder`](-participant-holder/index.md) |
| [removeParticipant](remove-participant.md) | `fun removeParticipant(participantId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setParticipants](set-participants.md) | `fun setParticipants(data: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeParticipant>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
