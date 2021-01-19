[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel.content](../index.md) / [ActiveContentViewModel](./index.md)

# ActiveContentViewModel

`class ActiveContentViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ActiveContentViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [setActiveContentLiveData](set-active-content-live-data.md) | `val setActiveContentLiveData: LiveData<SetActiveContentPayload>` |
| [slideChangedLiveData](slide-changed-live-data.md) | `val slideChangedLiveData: LiveData<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [syncPlayerStateLiveData](sync-player-state-live-data.md) | `val syncPlayerStateLiveData: LiveData<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`PlayerControlsEvent`](../../com.kme.kaltura.kmeapplication.view.view.content.controls/-player-controls-event/index.md)`?, `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>>` |

### Functions

| Name | Summary |
|---|---|
| [enabledControls](enabled-controls.md) | `fun enabledControls(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCookie](get-cookie.md) | `fun getCookie(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getFilesUrl](get-files-url.md) | `fun getFilesUrl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [subscribe](subscribe.md) | `fun subscribe(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
