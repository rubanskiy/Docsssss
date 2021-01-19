[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [ParticipantsViewModel](./index.md)

# ParticipantsViewModel

`class ParticipantsViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ParticipantsViewModel(kmeSdk: KME, gson: Gson)` |

### Properties

| Name | Summary |
|---|---|
| [allCamsStateLiveData](all-cams-state-live-data.md) | `val allCamsStateLiveData: LiveData<KmePermissionValue>` |
| [allCamsToggledByAdminLiveData](all-cams-toggled-by-admin-live-data.md) | `val allCamsToggledByAdminLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [allHandsDownByAdminLiveData](all-hands-down-by-admin-live-data.md) | `val allHandsDownByAdminLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [allMicsStateLiveData](all-mics-state-live-data.md) | `val allMicsStateLiveData: LiveData<KmePermissionValue>` |
| [allMicsToggledByAdminLiveData](all-mics-toggled-by-admin-live-data.md) | `val allMicsToggledByAdminLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [anyHandsRaisedStateLiveData](any-hands-raised-state-live-data.md) | `val anyHandsRaisedStateLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [camToggledByAdminLiveData](cam-toggled-by-admin-live-data.md) | `val camToggledByAdminLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [liveToggledByAdminLiveData](live-toggled-by-admin-live-data.md) | `val liveToggledByAdminLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [mediaStateChangedByAdminLiveData](media-state-changed-by-admin-live-data.md) | `val mediaStateChangedByAdminLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [micToggledByAdminLiveData](mic-toggled-by-admin-live-data.md) | `val micToggledByAdminLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [participantChangedLiveData](participant-changed-live-data.md) | `val participantChangedLiveData: LiveData<KmeParticipant>` |
| [participantHandRaisedLiveData](participant-hand-raised-live-data.md) | `val participantHandRaisedLiveData: LiveData<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>>` |
| [participants](participants.md) | `val participants: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeParticipant>` |
| [publicChatStateLiveData](public-chat-state-live-data.md) | `val publicChatStateLiveData: LiveData<KmePermissionValue>` |
| [userDisconnectedLiveData](user-disconnected-live-data.md) | `val userDisconnectedLiveData: LiveData<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [isParticipantJoined](is-participant-joined.md) | `fun isParticipantJoined(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onCleared](on-cleared.md) | `fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [putAllHandsDown](put-all-hands-down.md) | `fun putAllHandsDown(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRoomData](set-room-data.md) | `fun setRoomData(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [subscribe](subscribe.md) | `fun subscribe(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleAllCams](toggle-all-cams.md) | `fun toggleAllCams(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleAllCamsByAdmin](toggle-all-cams-by-admin.md) | `fun toggleAllCamsByAdmin(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleAllMics](toggle-all-mics.md) | `fun toggleAllMics(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleAllMicsByAdmin](toggle-all-mics-by-admin.md) | `fun toggleAllMicsByAdmin(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleParticipantCam](toggle-participant-cam.md) | `fun toggleParticipantCam(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleParticipantLive](toggle-participant-live.md) | `fun toggleParticipantLive(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleParticipantMicro](toggle-participant-micro.md) | `fun toggleParticipantMicro(participant: KmeParticipant): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [togglePublicChat](toggle-public-chat.md) | `fun togglePublicChat(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateAdminPanelState](update-admin-panel-state.md) | `fun updateAdminPanelState(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updatePublisherLive](update-publisher-live.md) | `fun updatePublisherLive(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateUserModeratorState](update-user-moderator-state.md) | `fun updateUserModeratorState(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, isModerator: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
