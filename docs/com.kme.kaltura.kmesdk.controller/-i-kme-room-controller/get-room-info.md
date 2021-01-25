[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomController](index.md) / [getRoomInfo](./get-room-info.md)

# getRoomInfo

`abstract fun getRoomInfo(alias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, checkPermission: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, withFiles: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, success: (response: `[`KmeGetRoomInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-room-info-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Getting room info by alias

### Parameters

`alias` - alias of a room

`checkPermission` -

`withFiles` -

`success` - function to handle success result. Contains [KmeGetRoomInfoResponse](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-room-info-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object