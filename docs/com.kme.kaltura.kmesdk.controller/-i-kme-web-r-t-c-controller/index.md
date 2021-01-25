[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeWebRTCController](./index.md)

# IKmeWebRTCController

`interface IKmeWebRTCController`

An interface for wrap actions with [IKmePeerConnectionController](../-i-kme-peer-connection-controller/index.md)

### Functions

| Name | Summary |
|---|---|
| [addPublisherPeerConnection](add-publisher-peer-connection.md) | `abstract fun addPublisherPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, renderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`, listener: `[`IKmePeerConnectionClientEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-client-events/index.md)`): `[`IKmePeerConnectionController`](../-i-kme-peer-connection-controller/index.md)`?`<br>Creates publisher connection |
| [addViewerPeerConnection](add-viewer-peer-connection.md) | `abstract fun addViewerPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, renderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`, listener: `[`IKmePeerConnectionClientEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-client-events/index.md)`): `[`IKmePeerConnectionController`](../-i-kme-peer-connection-controller/index.md)`?`<br>Creates a viewer connection |
| [disconnectAllConnections](disconnect-all-connections.md) | `abstract fun disconnectAllConnections(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disconnect all publisher/viewers connections |
| [disconnectPeerConnection](disconnect-peer-connection.md) | `abstract fun disconnectPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disconnect publisher/viewer connection by id |
| [getPeerConnection](get-peer-connection.md) | `abstract fun getPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`IKmePeerConnectionController`](../-i-kme-peer-connection-controller/index.md)`?`<br>Getting publisher/viewer connection by id |
| [getPublisherConnection](get-publisher-connection.md) | `abstract fun getPublisherConnection(): `[`IKmePeerConnectionController`](../-i-kme-peer-connection-controller/index.md)`?`<br>Getting publisher connection if exist |
| [setTurnServer](set-turn-server.md) | `abstract fun setTurnServer(turnUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, turnUser: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, turnCred: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting TURN server for RTC |

### Inheritors

| Name | Summary |
|---|---|
| [IKmeRoomController](../-i-kme-room-controller/index.md) | `interface IKmeRoomController : `[`IKmeWebSocketController`](../-i-kme-web-socket-controller/index.md)`, `[`IKmeWebRTCController`](./index.md)<br>An interface for room data |
| [KmeRoomService](../../com.kme.kaltura.kmesdk.service/-kme-room-service/index.md) | `class KmeRoomService : `[`Service`](https://developer.android.com/reference/android/app/Service.html)`, KmeKoinComponent, `[`IKmeWebSocketController`](../-i-kme-web-socket-controller/index.md)`, `[`IKmeWebRTCController`](./index.md)<br>Service wrapper under the room actions |
