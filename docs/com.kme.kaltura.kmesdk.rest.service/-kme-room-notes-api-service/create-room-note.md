[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomNotesApiService](index.md) / [createRoomNote](./create-room-note.md)

# createRoomNote

`@FormUrlEncoded @POST("note/create") abstract suspend fun createRoomNote(@Field("company_id") companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, @Field("room_id") roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`KmeRoomNoteCreateResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-create-response/index.md)

Creates a new note in the room

### Parameters

`companyId` - id of a company

`roomId` - id of a room

**Return**
[KmeRoomNoteCreateResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-create-response/index.md) object in success case

