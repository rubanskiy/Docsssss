[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.content.playkit](../index.md) / [IKmeMediaPlaybackListener](./index.md)

# IKmeMediaPlaybackListener

`interface IKmeMediaPlaybackListener`

An interface for media files playback

### Properties

| Name | Summary |
|---|---|
| [currentPosition](current-position.md) | `abstract val currentPosition: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Getting current playing position |
| [duration](duration.md) | `abstract val duration: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Getting duration of current media file |

### Functions

| Name | Summary |
|---|---|
| [addListener](add-listener.md) | `abstract fun <E : PKEvent?> addListener(groupId: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, type: `[`Class`](https://developer.android.com/reference/java/lang/Class.html)`<`[`E`](add-listener.md#E)`>, listener: Listener<`[`E`](add-listener.md#E)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adding listener for specific event`abstract fun addListener(groupId: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, type: `[`Enum`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)`<*>, listener: Listener<*>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adding event listener |
| [init](init.md) | `abstract fun init(config: `[`Config`](../-kme-media-view/-config/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Init media view |
| [isEnded](is-ended.md) | `abstract fun isEnded(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check is playback of media file is ended |
| [pause](pause.md) | `abstract fun pause(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Pause playback |
| [play](play.md) | `abstract fun play(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Start playback |
| [removeListeners](remove-listeners.md) | `abstract fun removeListeners(groupId: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Removing event listener |
| [replay](replay.md) | `abstract fun replay(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Replay playback |
| [seekTo](seek-to.md) | `abstract fun seekTo(seekTo: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Seek to position |
| [setMedia](set-media.md) | `abstract fun setMedia(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting media file url |

### Inheritors

| Name | Summary |
|---|---|
| [KmeMediaView](../-kme-media-view/index.md) | `class KmeMediaView : `[`FrameLayout`](https://developer.android.com/reference/android/widget/FrameLayout.html)`, `[`IKmeMediaPlaybackListener`](./index.md)<br>An implementation of view for media files playback |
