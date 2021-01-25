[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeWebRTCController](index.md) / [addPublisherPeerConnection](./add-publisher-peer-connection.md)

# addPublisherPeerConnection

`abstract fun addPublisherPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, renderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`, listener: `[`IKmePeerConnectionClientEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-client-events/index.md)`): `[`IKmePeerConnectionController`](../-i-kme-peer-connection-controller/index.md)`?`

Creates publisher connection

### Parameters

`requestedUserIdStream` - id of a stream

`renderer` - view for video rendering

`listener` - listener for p2p events

**Return**
publisher connection object as [IKmePeerConnectionController](../-i-kme-peer-connection-controller/index.md)

