[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.peerconnection](../index.md) / [IKmePeerConnection](index.md) / [createPeerConnection](./create-peer-connection.md)

# createPeerConnection

`abstract fun createPeerConnection(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, localVideoSink: VideoSink, remoteVideoSink: VideoSink, videoCapturer: VideoCapturer?, isPublisher: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, iceServers: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<IceServer>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Creates peer connection

### Parameters

`context` - application context

`localVideoSink` - local video sink

`remoteVideoSink` - remote video sink

`videoCapturer` - video capturer

`isPublisher` - indicates type of connection

`iceServers` - collection of ice servers