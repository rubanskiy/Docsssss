[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomNotesApiService](index.md) / [getRoomNotes](./get-room-notes.md)

# getRoomNotes

`@GET("note/getRoomNotes") abstract suspend fun getRoomNotes(@Query("company_id") companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, @Query("room_id") roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`KmeGetRoomNotesResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-get-room-notes-response/index.md)

Getting all notes for specific room

### Parameters

`companyId` - id of a company

`roomId` - id of a room

**Return**
[KmeGetRoomNotesResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-get-room-notes-response/index.md) object in success case

