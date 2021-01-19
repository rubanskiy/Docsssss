[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.view.content.controls](../index.md) / [VideoControlsView](./index.md)

# VideoControlsView

`class VideoControlsView : `[`BaseControlsView`](../-base-controls-view/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `VideoControlsView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`)`<br>`VideoControlsView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, attrs: `[`AttributeSet`](https://developer.android.com/reference/android/util/AttributeSet.html)`?)`<br>`VideoControlsView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, attrs: `[`AttributeSet`](https://developer.android.com/reference/android/util/AttributeSet.html)`?, defStyleAttr: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [autoHideTimeout](../-base-controls-view/auto-hide-timeout.md) | `var autoHideTimeout: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [controlsEventListener](../-base-controls-view/controls-event-listener.md) | `var controlsEventListener: `[`OnControlsEventListener`](../-base-controls-view/-on-controls-event-listener/index.md)`?` |
| [coroutineContext](../-base-controls-view/coroutine-context.md) | `open val coroutineContext: `[`CoroutineContext`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html) |
| [isPlaying](../-base-controls-view/is-playing.md) | `var isPlaying: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [seekBarChangeListener](../-base-controls-view/seek-bar-change-listener.md) | `var seekBarChangeListener: `[`OnSeekBarChangeListener`](../-base-controls-view/-on-seek-bar-change-listener/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [isControlsVisible](is-controls-visible.md) | `fun isControlsVisible(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setControlsMode](set-controls-mode.md) | `fun setControlsMode(isEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setControlsVisibility](set-controls-visibility.md) | `fun setControlsVisibility(doShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setPlayPauseVisibility](set-play-pause-visibility.md) | `fun setPlayPauseVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setProgressBarVisibility](set-progress-bar-visibility.md) | `fun setProgressBarVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarMode](set-seek-bar-mode.md) | `fun setSeekBarMode(isEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarProgress](set-seek-bar-progress.md) | `fun setSeekBarProgress(progress: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarSecondaryProgress](set-seek-bar-secondary-progress.md) | `fun setSeekBarSecondaryProgress(secondaryProgress: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarVisibility](set-seek-bar-visibility.md) | `fun setSeekBarVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimePosition](set-time-position.md) | `fun setTimePosition(timeSeconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, durationSeconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeVisibility](set-time-visibility.md) | `fun setTimeVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateUI](update-u-i.md) | `fun updateUI(event: `[`PlayerControlsEvent`](../-player-controls-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [formatTime](../-base-controls-view/format-time.md) | `fun formatTime(totalSeconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [onDetachedFromWindow](../-base-controls-view/on-detached-from-window.md) | `open fun onDetachedFromWindow(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [progressBarValue](../-base-controls-view/progress-bar-value.md) | `fun progressBarValue(position: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, duration: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [resetAutoHideControls](../-base-controls-view/reset-auto-hide-controls.md) | `fun resetAutoHideControls(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [gone](../../com.kme.kaltura.kmeapplication.util.extensions/android.view.-view/gone.md) | `fun `[`View`](https://developer.android.com/reference/android/view/View.html)`?.gone(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [invisible](../../com.kme.kaltura.kmeapplication.util.extensions/android.view.-view/invisible.md) | `fun `[`View`](https://developer.android.com/reference/android/view/View.html)`?.invisible(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isGone](../../com.kme.kaltura.kmeapplication.util.extensions/android.view.-view/is-gone.md) | `fun `[`View`](https://developer.android.com/reference/android/view/View.html)`?.isGone(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isInvisible](../../com.kme.kaltura.kmeapplication.util.extensions/android.view.-view/is-invisible.md) | `fun `[`View`](https://developer.android.com/reference/android/view/View.html)`?.isInvisible(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](../../com.kme.kaltura.kmeapplication.util.extensions/android.view.-view/is-visible.md) | `fun `[`View`](https://developer.android.com/reference/android/view/View.html)`?.isVisible(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [popup](../../com.kme.kaltura.kmeapplication.util.extensions/android.view.-view/popup.md) | `fun `[`View`](https://developer.android.com/reference/android/view/View.html)`.popup(menu: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, withIcons: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, gravity: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = Gravity.END, style: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = R.style.AppTheme_PopupStyle): PopupMenu` |
| [visible](../../com.kme.kaltura.kmeapplication.util.extensions/android.view.-view/visible.md) | `fun `[`View`](https://developer.android.com/reference/android/view/View.html)`?.visible(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
