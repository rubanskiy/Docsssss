[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomNotesController](index.md) / [deleteRoomNote](./delete-room-note.md)

# deleteRoomNote

`abstract fun deleteRoomNote(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, noteId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, success: (response: `[`KmeDeleteRoomNoteResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-delete-room-note-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Delete specific note

### Parameters

`roomId` - id of a room

`noteId` - id of a note

`success` - function to handle success result. Contains [KmeDeleteRoomNoteResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-delete-room-note-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object