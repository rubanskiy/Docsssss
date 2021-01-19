[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [RoomSettingsViewModel](./index.md)

# RoomSettingsViewModel

`class RoomSettingsViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomSettingsViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [chatSettingsChangedLiveData](chat-settings-changed-live-data.md) | `val chatSettingsChangedLiveData: LiveData<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<KmePermissionKey?, KmePermissionValue?>>` |
| [moderatorLiveData](moderator-live-data.md) | `val moderatorLiveData: LiveData<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>>` |
| [toggleAllCamsByAdminLiveData](toggle-all-cams-by-admin-live-data.md) | `val toggleAllCamsByAdminLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [toggleAllMicsByAdminLiveData](toggle-all-mics-by-admin-live-data.md) | `val toggleAllMicsByAdminLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [youModeratorLiveData](you-moderator-live-data.md) | `val youModeratorLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [subscribe](subscribe.md) | `fun subscribe(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
