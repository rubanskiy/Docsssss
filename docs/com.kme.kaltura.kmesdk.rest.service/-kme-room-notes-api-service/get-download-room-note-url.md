[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomNotesApiService](index.md) / [getDownloadRoomNoteUrl](./get-download-room-note-url.md)

# getDownloadRoomNoteUrl

`@FormUrlEncoded @POST("note/downloadNote") abstract suspend fun getDownloadRoomNoteUrl(@Field("room_id") roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, @Field("note_id") noteId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, @Field("saveToFiles") saveToFiles: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`KmeRoomNoteDownloadUrlResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-download-url-response/index.md)

Getting an url for download note as pdf file

### Parameters

`roomId` - id of a room

`noteId` - id of a note

`saveToFiles` - save to room files folder

**Return**
[KmeRoomNoteDownloadUrlResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-download-url-response/index.md) object in success case

