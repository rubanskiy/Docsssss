[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.adapter](../index.md) / [RenderersAdapter](./index.md)

# RenderersAdapter

`class RenderersAdapter : Adapter<`[`RendererHolder`](-renderer-holder/index.md)`>`

### Types

| Name | Summary |
|---|---|
| [RendererHolder](-renderer-holder/index.md) | `inner class RendererHolder : ViewHolder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RenderersAdapter(width: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, height: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [addRenderer](add-renderer.md) | `fun addRenderer(participant: KmeParticipant, renderer: KmeSurfaceRendererView): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getItemCount](get-item-count.md) | `fun getItemCount(): <ERROR CLASS>` |
| [getItemViewType](get-item-view-type.md) | `fun getItemViewType(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [onBindViewHolder](on-bind-view-holder.md) | `fun onBindViewHolder(holder: `[`RendererHolder`](-renderer-holder/index.md)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, payloads: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun onBindViewHolder(holder: `[`RendererHolder`](-renderer-holder/index.md)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateViewHolder](on-create-view-holder.md) | `fun onCreateViewHolder(parent: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`, viewType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`RendererHolder`](-renderer-holder/index.md) |
| [removeRendererFor](remove-renderer-for.md) | `fun removeRendererFor(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setIsModerator](set-is-moderator.md) | `fun setIsModerator(isModerator: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateAudioStateFor](update-audio-state-for.md) | `fun updateAudioStateFor(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun updateAudioStateFor(participantsToUpdate: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeParticipant>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateRaiseHandFor](update-raise-hand-for.md) | `fun updateRaiseHandFor(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateSpeakingStateFor](update-speaking-state-for.md) | `fun updateSpeakingStateFor(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateVideoStateFor](update-video-state-for.md) | `fun updateVideoStateFor(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun updateVideoStateFor(participantsToUpdate: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeParticipant>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [AUDIO_STATE_PAYLOAD](-a-u-d-i-o_-s-t-a-t-e_-p-a-y-l-o-a-d.md) | `const val AUDIO_STATE_PAYLOAD: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [BACKGROUND_PAYLOAD](-b-a-c-k-g-r-o-u-n-d_-p-a-y-l-o-a-d.md) | `const val BACKGROUND_PAYLOAD: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [HAND_RAISE_PAYLOAD](-h-a-n-d_-r-a-i-s-e_-p-a-y-l-o-a-d.md) | `const val HAND_RAISE_PAYLOAD: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [VIDEO_STATE_PAYLOAD](-v-i-d-e-o_-s-t-a-t-e_-p-a-y-l-o-a-d.md) | `const val VIDEO_STATE_PAYLOAD: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
