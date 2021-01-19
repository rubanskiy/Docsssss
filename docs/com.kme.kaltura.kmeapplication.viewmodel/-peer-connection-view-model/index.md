[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [PeerConnectionViewModel](./index.md)

# PeerConnectionViewModel

`class PeerConnectionViewModel : ViewModel, IKmePeerConnectionClientEvents`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PeerConnectionViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [cameraEnabledLiveData](camera-enabled-live-data.md) | `val cameraEnabledLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [liveEnabledLiveData](live-enabled-live-data.md) | `val liveEnabledLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [micEnabledLiveData](mic-enabled-live-data.md) | `val micEnabledLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [participantAddLiveData](participant-add-live-data.md) | `val participantAddLiveData: LiveData<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [participantMediaStateChangedLiveData](participant-media-state-changed-live-data.md) | `val participantMediaStateChangedLiveData: LiveData<UserMediaStateChangedPayload>` |
| [participantRemoveLiveData](participant-remove-live-data.md) | `val participantRemoveLiveData: LiveData<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [publisherAddLiveData](publisher-add-live-data.md) | `val publisherAddLiveData: LiveData<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [publisherAddedLiveData](publisher-added-live-data.md) | `val publisherAddedLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [speakerEnabledLiveData](speaker-enabled-live-data.md) | `val speakerEnabledLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [userSpeakingLiveData](user-speaking-live-data.md) | `val userSpeakingLiveData: LiveData<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>>` |

### Functions

| Name | Summary |
|---|---|
| [addRenderer](add-renderer.md) | `fun addRenderer(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, rendererView: KmeSurfaceRendererView): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isPublishing](is-publishing.md) | `fun isPublishing(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onCleared](on-cleared.md) | `fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onIceCandidate](on-ice-candidate.md) | `fun onIceCandidate(candidate: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onIceCandidatesRemoved](on-ice-candidates-removed.md) | `fun onIceCandidatesRemoved(candidates: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onIceConnected](on-ice-connected.md) | `fun onIceConnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onIceDisconnected](on-ice-disconnected.md) | `fun onIceDisconnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onIceGatheringDone](on-ice-gathering-done.md) | `fun onIceGatheringDone(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mediaServerId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onLocalDescription](on-local-description.md) | `fun onLocalDescription(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mediaServerId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, sdp: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPeerConnectionClosed](on-peer-connection-closed.md) | `fun onPeerConnectionClosed(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPeerConnectionCreated](on-peer-connection-created.md) | `fun onPeerConnectionCreated(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPeerConnectionError](on-peer-connection-error.md) | `fun onPeerConnectionError(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPeerConnectionStatsReady](on-peer-connection-stats-ready.md) | `fun onPeerConnectionStatsReady(reports: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onUserSpeaking](on-user-speaking.md) | `fun onUserSpeaking(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, isSpeaking: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRoomData](set-room-data.md) | `fun setRoomData(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [startPublish](start-publish.md) | `fun startPublish(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleCamByAdmin](toggle-cam-by-admin.md) | `fun toggleCamByAdmin(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, forAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleCamera](toggle-camera.md) | `fun toggleCamera(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleLiveByAdmin](toggle-live-by-admin.md) | `fun toggleLiveByAdmin(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleMic](toggle-mic.md) | `fun toggleMic(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleMicByAdmin](toggle-mic-by-admin.md) | `fun toggleMicByAdmin(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, forAll: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toggleSpeaker](toggle-speaker.md) | `fun toggleSpeaker(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
