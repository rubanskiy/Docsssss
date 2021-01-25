[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomNotesController](index.md) / [createRoomNote](./create-room-note.md)

# createRoomNote

`abstract fun createRoomNote(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, success: (response: `[`KmeRoomNoteCreateResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-create-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Creates a new note in the room

### Parameters

`companyId` - id of a company

`roomId` - id of a room

`success` - function to handle success result. Contains [KmeRoomNoteCreateResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-create-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object