[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller.impl](../index.md) / [KmePeerConnectionControllerImpl](./index.md)

# KmePeerConnectionControllerImpl

`class KmePeerConnectionControllerImpl : `[`IKmePeerConnectionController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-peer-connection-controller/index.md)`, `[`IKmePeerConnectionEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-events/index.md)

An implementation for p2p connection

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmePeerConnectionControllerImpl(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, gson: Gson)`<br>An implementation for p2p connection |

### Functions

| Name | Summary |
|---|---|
| [createOffer](create-offer.md) | `fun createOffer(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates an offers |
| [createPeerConnection](create-peer-connection.md) | `fun createPeerConnection(isPublisher: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, listener: `[`IKmePeerConnectionClientEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-client-events/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates p2p connection |
| [disconnectPeerConnection](disconnect-peer-connection.md) | `fun disconnectPeerConnection(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Closes actual p2p connection |
| [enableAudio](enable-audio.md) | `fun enableAudio(isEnable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Toggle audio |
| [enableCamera](enable-camera.md) | `fun enableCamera(isEnable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Toggle camera |
| [onIceCandidate](on-ice-candidate.md) | `fun onIceCandidate(candidate: IceCandidate): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local Ice candidate is generated |
| [onIceCandidatesRemoved](on-ice-candidates-removed.md) | `fun onIceCandidatesRemoved(candidates: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<IceCandidate>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local ICE candidates are removed |
| [onIceConnected](on-ice-connected.md) | `fun onIceConnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once connection is established (IceConnectionState is CONNECTED) |
| [onIceDisconnected](on-ice-disconnected.md) | `fun onIceDisconnected(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once connection is closed (IceConnectionState is DISCONNECTED) |
| [onIceGatheringDone](on-ice-gathering-done.md) | `fun onIceGatheringDone(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once ice gathering is complete (IceGatheringDone is COMPLETE) |
| [onLocalDescription](on-local-description.md) | `fun onLocalDescription(sdp: SessionDescription): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once local SDP is created and set |
| [onPeerConnectionClosed](on-peer-connection-closed.md) | `fun onPeerConnectionClosed(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection is closed |
| [onPeerConnectionCreated](on-peer-connection-created.md) | `fun onPeerConnectionCreated(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peerConnection instance created |
| [onPeerConnectionError](on-peer-connection-error.md) | `fun onPeerConnectionError(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection error happened |
| [onPeerConnectionStatsReady](on-peer-connection-stats-ready.md) | `fun onPeerConnectionStatsReady(reports: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<StatsReport>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired once peer connection statistics is ready |
| [onUserSpeaking](on-user-speaking.md) | `fun onUserSpeaking(isSpeaking: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Callback fired to indicate current talking user |
| [setLocalRenderer](set-local-renderer.md) | `fun setLocalRenderer(localRenderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting view for local stream rendering |
| [setMediaServerId](set-media-server-id.md) | `fun setMediaServerId(mediaServerId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting media server id for data relay |
| [setRemoteRenderer](set-remote-renderer.md) | `fun setRemoteRenderer(remoteRenderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting view for remote stream rendering |
| [setRemoteSdp](set-remote-sdp.md) | `fun setRemoteSdp(type: `[`KmeSdpType`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-sdp-type/index.md)`, sdp: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting remote SDP |
| [setTurnServer](set-turn-server.md) | `fun setTurnServer(turnUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, turnUser: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, turnCred: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting TURN server for RTC. Build ICE servers collection |
| [switchCamera](switch-camera.md) | `fun switchCamera(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Switch between existing cameras |
