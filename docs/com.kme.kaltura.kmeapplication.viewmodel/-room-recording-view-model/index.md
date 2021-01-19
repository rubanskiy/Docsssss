[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [RoomRecordingViewModel](./index.md)

# RoomRecordingViewModel

`class RoomRecordingViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomRecordingViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [conversionCompletedLiveData](conversion-completed-live-data.md) | `val conversionCompletedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [recordCompletedLiveData](record-completed-live-data.md) | `val recordCompletedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [recordDurationLiveData](record-duration-live-data.md) | `val recordDurationLiveData: LiveData<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [recordFailedLiveData](record-failed-live-data.md) | `val recordFailedLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [recordInitiatedLiveData](record-initiated-live-data.md) | `val recordInitiatedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [recordLiveData](record-live-data.md) | `val recordLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [recordStartingLiveData](record-starting-live-data.md) | `val recordStartingLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [recordStateInitializingLiveData](record-state-initializing-live-data.md) | `val recordStateInitializingLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [recordStateReadyToStartLiveData](record-state-ready-to-start-live-data.md) | `val recordStateReadyToStartLiveData: LiveData<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>>` |
| [recordStateReadyToStopLiveData](record-state-ready-to-stop-live-data.md) | `val recordStateReadyToStopLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [uploadCompletedLiveData](upload-completed-live-data.md) | `val uploadCompletedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [askForRecordingAction](ask-for-recording-action.md) | `fun askForRecordingAction(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isRecordingEnabled](is-recording-enabled.md) | `fun isRecordingEnabled(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mapAvailableVariants](map-available-variants.md) | `fun mapAvailableVariants(variants: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>, prefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, minutesStr: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, hourStr: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, hoursStr: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [onCleared](on-cleared.md) | `fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRoomData](set-room-data.md) | `fun setRoomData(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [startRecording](start-recording.md) | `fun startRecording(recordDuration: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [stopRecording](stop-recording.md) | `fun stopRecording(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [subscribe](subscribe.md) | `fun subscribe(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
