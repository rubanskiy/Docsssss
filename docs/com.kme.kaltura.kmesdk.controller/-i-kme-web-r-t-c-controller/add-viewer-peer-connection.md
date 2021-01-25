[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeWebRTCController](index.md) / [addViewerPeerConnection](./add-viewer-peer-connection.md)

# addViewerPeerConnection

`abstract fun addViewerPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, renderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`, listener: `[`IKmePeerConnectionClientEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-client-events/index.md)`): `[`IKmePeerConnectionController`](../-i-kme-peer-connection-controller/index.md)`?`

Creates a viewer connection

### Parameters

`requestedUserIdStream` -

`renderer` - view for video rendering

`listener` - listener for p2p events

**Return**
viewer connection object as [IKmePeerConnectionController](../-i-kme-peer-connection-controller/index.md)

