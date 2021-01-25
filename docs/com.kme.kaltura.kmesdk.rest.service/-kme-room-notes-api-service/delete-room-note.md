[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomNotesApiService](index.md) / [deleteRoomNote](./delete-room-note.md)

# deleteRoomNote

`@FormUrlEncoded @POST("note/delete") abstract suspend fun deleteRoomNote(@Field("room_id") roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, @Field("note_id") noteId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`KmeDeleteRoomNoteResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-delete-room-note-response/index.md)

Delete specific note

### Parameters

`roomId` - id of a room

`noteId` - id of a note

**Return**
[KmeDeleteRoomNoteResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-delete-room-note-response/index.md) object in success case

