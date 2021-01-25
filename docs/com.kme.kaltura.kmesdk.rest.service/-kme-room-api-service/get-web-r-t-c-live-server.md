[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomApiService](index.md) / [getWebRTCLiveServer](./get-web-r-t-c-live-server.md)

# getWebRTCLiveServer

`@GET("room/getWebrtcLiveServer") abstract suspend fun getWebRTCLiveServer(@Query("room_alias") roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, @Query("device_type") deviceType: `[`KmePlatformType`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-platform-type/index.md)` = KmePlatformType.MOBILE): `[`KmeGetWebRTCServerResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-web-r-t-c-server-response/index.md)

Getting data for p2p connection

### Parameters

`roomAlias` - alias of a room

`deviceType` - device type flag

**Return**
[KmeGetWebRTCServerResponse](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-web-r-t-c-server-response/index.md) object in success case

