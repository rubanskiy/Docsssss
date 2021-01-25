[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.service](../index.md) / [KmeRoomService](./index.md)

# KmeRoomService

`class KmeRoomService : `[`Service`](https://developer.android.com/reference/android/app/Service.html)`, KmeKoinComponent, `[`IKmeWebSocketController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-web-socket-controller/index.md)`, `[`IKmeWebRTCController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-web-r-t-c-controller/index.md)

Service wrapper under the room actions

### Types

| Name | Summary |
|---|---|
| [RoomServiceBinder](-room-service-binder/index.md) | `inner class RoomServiceBinder : `[`Binder`](https://developer.android.com/reference/android/os/Binder.html) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeRoomService()`<br>Service wrapper under the room actions |

### Functions

| Name | Summary |
|---|---|
| [addPublisherPeerConnection](add-publisher-peer-connection.md) | `fun addPublisherPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, renderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`, listener: `[`IKmePeerConnectionClientEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-client-events/index.md)`): `[`IKmePeerConnectionController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-peer-connection-controller/index.md)`?`<br>Creates publisher connection |
| [addViewerPeerConnection](add-viewer-peer-connection.md) | `fun addViewerPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, renderer: `[`KmeSurfaceRendererView`](../../com.kme.kaltura.kmesdk.webrtc.view/-kme-surface-renderer-view/index.md)`, listener: `[`IKmePeerConnectionClientEvents`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection-client-events/index.md)`): `[`IKmePeerConnectionController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-peer-connection-controller/index.md)`?`<br>Creates a viewer connection |
| [connect](connect.md) | `fun connect(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, isReconnect: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, listener: `[`IKmeWSConnectionListener`](../../com.kme.kaltura.kmesdk.ws/-i-kme-w-s-connection-listener/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Establish socket connection |
| [disconnect](disconnect.md) | `fun disconnect(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disconnect from the room. Destroy all related connections |
| [disconnectAllConnections](disconnect-all-connections.md) | `fun disconnectAllConnections(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disconnect all publisher/viewers connections |
| [disconnectPeerConnection](disconnect-peer-connection.md) | `fun disconnectPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disconnect publisher/viewer connection by id |
| [getPeerConnection](get-peer-connection.md) | `fun getPeerConnection(requestedUserIdStream: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`IKmePeerConnectionController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-peer-connection-controller/index.md)`?`<br>Getting publisher/viewer connection by id |
| [getPublisherConnection](get-publisher-connection.md) | `fun getPublisherConnection(): `[`IKmePeerConnectionController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-peer-connection-controller/index.md)`?`<br>Getting publisher connection if exist |
| [isConnected](is-connected.md) | `fun isConnected(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check is socket connected |
| [onBind](on-bind.md) | `fun onBind(intent: `[`Intent`](https://developer.android.com/reference/android/content/Intent.html)`?): `[`IBinder`](https://developer.android.com/reference/android/os/IBinder.html) |
| [onCreate](on-create.md) | `fun onCreate(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDestroy](on-destroy.md) | `fun onDestroy(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStartCommand](on-start-command.md) | `fun onStartCommand(intent: `[`Intent`](https://developer.android.com/reference/android/content/Intent.html)`?, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, startId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [onUnbind](on-unbind.md) | `fun onUnbind(intent: `[`Intent`](https://developer.android.com/reference/android/content/Intent.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [send](send.md) | `fun send(message: `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<out `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Send message via socket |
| [setTurnServer](set-turn-server.md) | `fun setTurnServer(turnUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, turnUser: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, turnCred: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting TURN server for RTC |
