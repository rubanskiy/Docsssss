[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeWebSocketController](./index.md)

# IKmeWebSocketController

`interface IKmeWebSocketController`

An interface for communication with socket in the room

### Functions

| Name | Summary |
|---|---|
| [connect](connect.md) | `abstract fun connect(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, isReconnect: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, listener: `[`IKmeWSConnectionListener`](../../com.kme.kaltura.kmesdk.ws/-i-kme-w-s-connection-listener/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Establish socket connection |
| [disconnect](disconnect.md) | `abstract fun disconnect(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Disconnect socket connection |
| [isConnected](is-connected.md) | `abstract fun isConnected(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check is socket connected |
| [send](send.md) | `abstract fun send(message: `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<out `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Send message via socket |

### Inheritors

| Name | Summary |
|---|---|
| [IKmeRoomController](../-i-kme-room-controller/index.md) | `interface IKmeRoomController : `[`IKmeWebSocketController`](./index.md)`, `[`IKmeWebRTCController`](../-i-kme-web-r-t-c-controller/index.md)<br>An interface for room data |
| [KmeRoomService](../../com.kme.kaltura.kmesdk.service/-kme-room-service/index.md) | `class KmeRoomService : `[`Service`](https://developer.android.com/reference/android/app/Service.html)`, KmeKoinComponent, `[`IKmeWebSocketController`](./index.md)`, `[`IKmeWebRTCController`](../-i-kme-web-r-t-c-controller/index.md)<br>Service wrapper under the room actions |
