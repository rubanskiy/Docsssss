[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.peerconnection](../index.md) / [IKmePeerConnection](./index.md)

# IKmePeerConnection

`interface IKmePeerConnection`

An interface for actions under WebRTC peer connection object

### Functions

| Name | Summary |
|---|---|
| [addRemoteIceCandidate](add-remote-ice-candidate.md) | `abstract fun addRemoteIceCandidate(candidate: IceCandidate?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Handle adding ICE candidates |
| [close](close.md) | `abstract fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Closes actual connection |
| [createAnswer](create-answer.md) | `abstract fun createAnswer(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates an answer |
| [createOffer](create-offer.md) | `abstract fun createOffer(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates an offers |
| [createPeerConnection](create-peer-connection.md) | `abstract fun createPeerConnection(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, localVideoSink: VideoSink, remoteVideoSink: VideoSink, videoCapturer: VideoCapturer?, isPublisher: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, iceServers: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<IceServer>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates peer connection |
| [createPeerConnectionFactory](create-peer-connection-factory.md) | `abstract fun createPeerConnectionFactory(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, events: `[`IKmePeerConnectionEvents`](../-i-kme-peer-connection-events/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates peer connection factory |
| [getRenderContext](get-render-context.md) | `abstract fun getRenderContext(): Context?`<br>Getting rendering context for WebRTC |
| [removeRemoteIceCandidates](remove-remote-ice-candidates.md) | `abstract fun removeRemoteIceCandidates(candidates: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<IceCandidate>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Handle remove remote ICE candidates |
| [setAudioEnabled](set-audio-enabled.md) | `abstract fun setAudioEnabled(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Toggle audio |
| [setRemoteDescription](set-remote-description.md) | `abstract fun setRemoteDescription(sdp: SessionDescription): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting remote SDP |
| [setVideoEnabled](set-video-enabled.md) | `abstract fun setVideoEnabled(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Toggle video |
| [startVideoSource](start-video-source.md) | `abstract fun startVideoSource(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Enable outgoing video stream |
| [stopVideoSource](stop-video-source.md) | `abstract fun stopVideoSource(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disable outgoing video stream |
| [switchCamera](switch-camera.md) | `abstract fun switchCamera(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Switch between existing cameras |

### Inheritors

| Name | Summary |
|---|---|
| [KmePeerConnectionImpl](../../com.kme.kaltura.kmesdk.webrtc.peerconnection.impl/-kme-peer-connection-impl/index.md) | `class KmePeerConnectionImpl : `[`IKmePeerConnection`](./index.md)`, `[`KmeSoundAmplitudeListener`](../../com.kme.kaltura.kmesdk.webrtc.stats/-kme-sound-amplitude-listener/index.md)<br>An implementation actions under WebRTC peer connection object |
