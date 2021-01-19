[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [RoomInfoViewModel](./index.md)

# RoomInfoViewModel

`class RoomInfoViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomInfoViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [isLoadingLiveData](is-loading-live-data.md) | `val isLoadingLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [roomInfoErrorLiveData](room-info-error-live-data.md) | `val roomInfoErrorLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [roomInfoLiveData](room-info-live-data.md) | `val roomInfoLiveData: LiveData<KmeBaseRoom>` |

### Functions

| Name | Summary |
|---|---|
| [fetchRoomInfo](fetch-room-info.md) | `fun fetchRoomInfo(roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
