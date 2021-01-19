[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel.content](../index.md) / [DesktopShareViewModel](./index.md)

# DesktopShareViewModel

`class DesktopShareViewModel : ViewModel, IKmePeerConnectionClientEvents`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `DesktopShareViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [desktopShareHDQualityLiveData](desktop-share-h-d-quality-live-data.md) | `val desktopShareHDQualityLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [isDesktopShareActiveLiveData](is-desktop-share-active-live-data.md) | `val isDesktopShareActiveLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
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
| [setRenderer](set-renderer.md) | `fun setRenderer(renderer: KmeSurfaceRendererView): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRoomData](set-room-data.md) | `fun setRoomData(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [subscribe](subscribe.md) | `fun subscribe(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
