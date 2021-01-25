[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomApiService](index.md) / [getRoomInfo](./get-room-info.md)

# getRoomInfo

`@GET("room/roomInfoByAlias") abstract suspend fun getRoomInfo(@Query("alias") alias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, @Query("with_viewed_files") withFiles: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, @Query("check_permission") checkPermission: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`KmeGetRoomInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-room-info-response/index.md)

Getting room info by alias

### Parameters

`alias` - alias of a room

`withFiles` -

`checkPermission` -

**Return**
[KmeGetRoomInfoResponse](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-room-info-response/index.md) object in success case

