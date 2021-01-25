[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomController](index.md) / [getWebRTCLiveServer](./get-web-r-t-c-live-server.md)

# getWebRTCLiveServer

`abstract fun getWebRTCLiveServer(roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`KmeGetWebRTCServerResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-web-r-t-c-server-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Getting data for p2p connection

### Parameters

`roomAlias` - alias of a room

`success` - function to handle success result. Contains [KmeGetWebRTCServerResponse](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-web-r-t-c-server-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object