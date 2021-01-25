[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomNotesController](index.md) / [getRoomNotes](./get-room-notes.md)

# getRoomNotes

`abstract fun getRoomNotes(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, success: (response: `[`KmeGetRoomNotesResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-get-room-notes-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Getting all notes for specific room

### Parameters

`companyId` - id of a company

`roomId` - id of a room

`success` - function to handle success result. Contains [KmeGetRoomNotesResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-get-room-notes-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object