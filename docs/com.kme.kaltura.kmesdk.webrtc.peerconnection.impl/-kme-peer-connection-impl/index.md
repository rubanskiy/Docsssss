[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.peerconnection.impl](../index.md) / [KmePeerConnectionImpl](./index.md)

# KmePeerConnectionImpl

`class KmePeerConnectionImpl : `[`IKmePeerConnection`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection/index.md)`, `[`KmeSoundAmplitudeListener`](../../com.kme.kaltura.kmesdk.webrtc.stats/-kme-sound-amplitude-listener/index.md)

An implementation actions under WebRTC peer connection object

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmePeerConnectionImpl()`<br>An implementation actions under WebRTC peer connection object |

### Functions

| Name | Summary |
|---|---|
| [addRemoteIceCandidate](add-remote-ice-candidate.md) | `fun addRemoteIceCandidate(candidate: IceCandidate?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Handle adding ICE candidate |
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Closes actual connection |
| [createAnswer](create-answer.md) | `fun createAnswer(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates an answer |
| [createOffer](create-offer.md) | `fun createOffer(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates an offers |
| [createPeerConnection](create-peer-connection.md) | `fun createPeerConnection(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, localVideoSink: VideoSink, remoteVideoSink: VideoSink, videoCapturer: VideoCapturer?, isPublisher: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, iceServers: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<IceServer>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates peer connection |
| [createPeerConnectionFactory](create-peer-connection-factory.md) | `fun createPeerConnectionFactory(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, events: `[`IKmePeerConnectionEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-events/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Creates peer connection factory |
| [getRenderContext](get-render-context.md) | `fun getRenderContext(): Context?`<br>Getting rendering context for WebRTC |
| [onAmplitudeMeasured](on-amplitude-measured.md) | `fun onAmplitudeMeasured(bringToFront: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, amplitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Fired once sound amplitude measured |
| [removeRemoteIceCandidates](remove-remote-ice-candidates.md) | `fun removeRemoteIceCandidates(candidates: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<IceCandidate>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Handle remove remote ICE candidates |
| [setAudioEnabled](set-audio-enabled.md) | `fun setAudioEnabled(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Toggle audio |
| [setRemoteDescription](set-remote-description.md) | `fun setRemoteDescription(sdp: SessionDescription): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting remote SDP |
| [setVideoEnabled](set-video-enabled.md) | `fun setVideoEnabled(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Toggle video |
| [setVideoMaxBitrate](set-video-max-bitrate.md) | `fun setVideoMaxBitrate(maxBitrateKbps: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Change bitrate parameters of local video |
| [startVideoSource](start-video-source.md) | `fun startVideoSource(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Enable outgoing video stream |
| [stopVideoSource](stop-video-source.md) | `fun stopVideoSource(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disable outgoing video stream |
| [switchCamera](switch-camera.md) | `fun switchCamera(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Switch between existing cameras |

### Companion Object Properties

| Name | Summary |
|---|---|
| [AUDIO_TRACK_ID](-a-u-d-i-o_-t-r-a-c-k_-i-d.md) | `const val AUDIO_TRACK_ID: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
