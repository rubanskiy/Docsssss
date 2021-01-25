[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.peerconnection](../index.md) / [IKmePeerConnectionEvents](./index.md)

# IKmePeerConnectionEvents

`interface IKmePeerConnectionEvents`

An interface for internal p2p connection events

### Functions

| Name | Summary |
|---|---|
| [onIceCandidate](on-ice-candidate.md) | `abstract fun onIceCandidate(candidate: IceCandidate): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local Ice candidate is generated |
| [onIceCandidatesRemoved](on-ice-candidates-removed.md) | `abstract fun onIceCandidatesRemoved(candidates: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<IceCandidate>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local ICE candidates are removed |
| [onIceConnected](on-ice-connected.md) | `abstract fun onIceConnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once connection is established (IceConnectionState is CONNECTED) |
| [onIceDisconnected](on-ice-disconnected.md) | `abstract fun onIceDisconnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once connection is closed (IceConnectionState is DISCONNECTED) |
| [onIceGatheringDone](on-ice-gathering-done.md) | `abstract fun onIceGatheringDone(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once ice gathering is complete (IceGatheringDone is COMPLETE) |
| [onLocalDescription](on-local-description.md) | `abstract fun onLocalDescription(sdp: SessionDescription): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local SDP is created and set |
| [onPeerConnectionClosed](on-peer-connection-closed.md) | `abstract fun onPeerConnectionClosed(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection is closed |
| [onPeerConnectionCreated](on-peer-connection-created.md) | `abstract fun onPeerConnectionCreated(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peerConnection instance created |
| [onPeerConnectionError](on-peer-connection-error.md) | `abstract fun onPeerConnectionError(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection error happened |
| [onPeerConnectionStatsReady](on-peer-connection-stats-ready.md) | `abstract fun onPeerConnectionStatsReady(reports: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<StatsReport>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection statistics is ready |
| [onUserSpeaking](on-user-speaking.md) | `abstract fun onUserSpeaking(isSpeaking: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired to indicate current talking user |

### Inheritors

| Name | Summary |
|---|---|
| [KmePeerConnectionControllerImpl](../../com.kme.kaltura.kmesdk.controller.impl/-kme-peer-connection-controller-impl/index.md) | `class KmePeerConnectionControllerImpl : `[`IKmePeerConnectionController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-peer-connection-controller/index.md)`, `[`IKmePeerConnectionEvents`](./index.md)<br>An implementation for p2p connection |
