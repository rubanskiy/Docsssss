[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.content.playkit](../index.md) / [KmeMediaView](./index.md)

# KmeMediaView

`class KmeMediaView : `[`FrameLayout`](https://developer.android.com/reference/android/widget/FrameLayout.html)`, `[`IKmeMediaPlaybackListener`](../-i-kme-media-playback-listener/index.md)

An implementation of view for media files playback

### Types

| Name | Summary |
|---|---|
| [Config](-config/index.md) | `class Config` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeMediaView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, attrs: `[`AttributeSet`](https://developer.android.com/reference/android/util/AttributeSet.html)`? = null, defStyleAttr: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0)`<br>An implementation of view for media files playback |

### Properties

| Name | Summary |
|---|---|
| [currentPosition](current-position.md) | `val currentPosition: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Getting current playing position |
| [duration](duration.md) | `val duration: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Getting duration of current media file |

### Functions

| Name | Summary |
|---|---|
| [addListener](add-listener.md) | `fun <E : PKEvent?> addListener(groupId: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, type: `[`Class`](https://developer.android.com/reference/java/lang/Class.html)`<`[`E`](add-listener.md#E)`>, listener: Listener<`[`E`](add-listener.md#E)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adding listener for specific event`fun addListener(groupId: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, type: `[`Enum`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)`<*>, listener: Listener<*>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adding event listener |
| [init](init.md) | `fun init(config: `[`Config`](-config/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Init media view |
| [isEnded](is-ended.md) | `fun isEnded(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check is playback of media file is ended |
| [isYoutube](is-youtube.md) | `fun isYoutube(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [pause](pause.md) | `fun pause(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Pause playback |
| [play](play.md) | `fun play(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Start playback |
| [release](release.md) | `fun release(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [removeListeners](remove-listeners.md) | `fun removeListeners(groupId: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Removing event listener |
| [replay](replay.md) | `fun replay(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Replay playback |
| [seekTo](seek-to.md) | `fun seekTo(seekTo: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Seek to position |
| [setMedia](set-media.md) | `fun setMedia(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting media file url |

### Companion Object Properties

| Name | Summary |
|---|---|
| [ENTRY_ID](-e-n-t-r-y_-i-d.md) | `const val ENTRY_ID: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [HTTP_PROVIDER_ID](-h-t-t-p_-p-r-o-v-i-d-e-r_-i-d.md) | `const val HTTP_PROVIDER_ID: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [MEDIA_SOURCE_ID](-m-e-d-i-a_-s-o-u-r-c-e_-i-d.md) | `const val MEDIA_SOURCE_ID: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
