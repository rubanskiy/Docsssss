[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.peerconnection](../index.md) / [IKmePeerConnectionClientEvents](./index.md)

# IKmePeerConnectionClientEvents

`interface IKmePeerConnectionClientEvents`

An interface for p2p connection events

### Functions

| Name | Summary |
|---|---|
| [onIceCandidate](on-ice-candidate.md) | `abstract fun onIceCandidate(candidate: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local Ice candidate is generated. |
| [onIceCandidatesRemoved](on-ice-candidates-removed.md) | `abstract fun onIceCandidatesRemoved(candidates: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local ICE candidates are removed. |
| [onIceConnected](on-ice-connected.md) | `abstract fun onIceConnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once connection is established (IceConnectionState is CONNECTED). |
| [onIceDisconnected](on-ice-disconnected.md) | `abstract fun onIceDisconnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once connection is closed (IceConnectionState is DISCONNECTED). |
| [onIceGatheringDone](on-ice-gathering-done.md) | `abstract fun onIceGatheringDone(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mediaServerId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once ice gathering is complete (IceGatheringDone is COMPLETE). |
| [onLocalDescription](on-local-description.md) | `abstract fun onLocalDescription(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mediaServerId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, sdp: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local SDP is created and set. |
| [onPeerConnectionClosed](on-peer-connection-closed.md) | `abstract fun onPeerConnectionClosed(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection is closed. |
| [onPeerConnectionCreated](on-peer-connection-created.md) | `abstract fun onPeerConnectionCreated(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peerConnection instance created |
| [onPeerConnectionError](on-peer-connection-error.md) | `abstract fun onPeerConnectionError(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection error happened. |
| [onPeerConnectionStatsReady](on-peer-connection-stats-ready.md) | `abstract fun onPeerConnectionStatsReady(reports: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection statistics is ready. |
| [onUserSpeaking](on-user-speaking.md) | `abstract fun onUserSpeaking(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, isSpeaking: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired to indicate current talking user |
