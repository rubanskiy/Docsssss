[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomApiService](index.md) / [getRooms](./get-rooms.md)

# getRooms

`@GET("room/getRoomListForCompany") abstract suspend fun getRooms(@Query("company_id") companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, @Query("page_number") pages: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, @Query("limit") limit: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`KmeGetRoomsResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-rooms-response/index.md)

Getting all rooms for specific company

### Parameters

`companyId` - id of a company

`pages` - page number

`limit` - count of rooms per page

**Return**
[KmeGetRoomsResponse](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-get-rooms-response/index.md) object in success case

