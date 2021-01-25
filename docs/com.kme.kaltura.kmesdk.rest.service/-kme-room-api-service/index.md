[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomApiService](./index.md)

# KmeRoomApiService

`interface KmeRoomApiService`

An interface for room data API calls

### Functions

| Name | Summary |
|---|---|
| [getRoomInfo](get-room-info.md) | `abstract suspend fun getRoomInfo(alias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, withFiles: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, checkPermission: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`KmeGetRoomInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-room-info-response/index.md)<br>Getting room info by alias |
| [getRooms](get-rooms.md) | `abstract suspend fun getRooms(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, pages: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, limit: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`KmeGetRoomsResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-rooms-response/index.md)<br>Getting all rooms for specific company |
| [getWebRTCLiveServer](get-web-r-t-c-live-server.md) | `abstract suspend fun getWebRTCLiveServer(roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, deviceType: `[`KmePlatformType`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-platform-type/index.md)` = KmePlatformType.MOBILE): `[`KmeGetWebRTCServerResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-web-r-t-c-server-response/index.md)<br>Getting data for p2p connection |
