[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomNotesController](index.md) / [renameRoomNote](./rename-room-note.md)

# renameRoomNote

`abstract fun renameRoomNote(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, noteId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`KmeRoomNoteRenameResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-rename-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Renames specific note

### Parameters

`roomId` - id of a room

`noteId` - id of a note

`name` - new name for the note

`success` - function to handle success result. Contains [KmeRoomNoteRenameResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-rename-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object