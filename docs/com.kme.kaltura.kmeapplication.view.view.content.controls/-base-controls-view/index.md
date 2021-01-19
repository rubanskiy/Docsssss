[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.view.content.controls](../index.md) / [BaseControlsView](./index.md)

# BaseControlsView

`abstract class BaseControlsView : `[`FrameLayout`](https://developer.android.com/reference/android/widget/FrameLayout.html)`, CoroutineScope`

### Types

| Name | Summary |
|---|---|
| [OnControlsEventListener](-on-controls-event-listener/index.md) | `interface OnControlsEventListener` |
| [OnSeekBarChangeListener](-on-seek-bar-change-listener/index.md) | `interface OnSeekBarChangeListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BaseControlsView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`)`<br>`BaseControlsView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, attrs: `[`AttributeSet`](https://developer.android.com/reference/android/util/AttributeSet.html)`?)`<br>`BaseControlsView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, attrs: `[`AttributeSet`](https://developer.android.com/reference/android/util/AttributeSet.html)`?, defStyleAttr: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [autoHideTimeout](auto-hide-timeout.md) | `var autoHideTimeout: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [controlsEventListener](controls-event-listener.md) | `var controlsEventListener: `[`OnControlsEventListener`](-on-controls-event-listener/index.md)`?` |
| [coroutineContext](coroutine-context.md) | `open val coroutineContext: `[`CoroutineContext`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html) |
| [isPlaying](is-playing.md) | `var isPlaying: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [seekBarChangeListener](seek-bar-change-listener.md) | `var seekBarChangeListener: `[`OnSeekBarChangeListener`](-on-seek-bar-change-listener/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [formatTime](format-time.md) | `fun formatTime(totalSeconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [isControlsVisible](is-controls-visible.md) | `abstract fun isControlsVisible(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onDetachedFromWindow](on-detached-from-window.md) | `open fun onDetachedFromWindow(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [progressBarValue](progress-bar-value.md) | `fun progressBarValue(position: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, duration: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [resetAutoHideControls](reset-auto-hide-controls.md) | `fun resetAutoHideControls(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setControlsMode](set-controls-mode.md) | `abstract fun setControlsMode(isEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setControlsVisibility](set-controls-visibility.md) | `open fun setControlsVisibility(doShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setPlayPauseVisibility](set-play-pause-visibility.md) | `abstract fun setPlayPauseVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setProgressBarVisibility](set-progress-bar-visibility.md) | `abstract fun setProgressBarVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarMode](set-seek-bar-mode.md) | `abstract fun setSeekBarMode(isEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarProgress](set-seek-bar-progress.md) | `abstract fun setSeekBarProgress(progress: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarSecondaryProgress](set-seek-bar-secondary-progress.md) | `abstract fun setSeekBarSecondaryProgress(secondaryProgress: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSeekBarVisibility](set-seek-bar-visibility.md) | `abstract fun setSeekBarVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimePosition](set-time-position.md) | `abstract fun setTimePosition(timeSeconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, durationSeconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeVisibility](set-time-visibility.md) | `abstract fun setTimeVisibility(toShow: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateUI](update-u-i.md) | `abstract fun updateUI(event: `[`PlayerControlsEvent`](../-player-controls-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [DEFAULT_AUTO_HIDE_TIMEOUT](-d-e-f-a-u-l-t_-a-u-t-o_-h-i-d-e_-t-i-m-e-o-u-t.md) | `const val DEFAULT_AUTO_HIDE_TIMEOUT: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [PROGRESS_BAR_MAX](-p-r-o-g-r-e-s-s_-b-a-r_-m-a-x.md) | `const val PROGRESS_BAR_MAX: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

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

### Inheritors

| Name | Summary |
|---|---|
| [VideoControlsView](../-video-controls-view/index.md) | `class VideoControlsView : `[`BaseControlsView`](./index.md) |
