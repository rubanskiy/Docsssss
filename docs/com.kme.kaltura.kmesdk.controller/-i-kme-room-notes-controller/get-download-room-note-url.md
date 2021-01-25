[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomNotesController](index.md) / [getDownloadRoomNoteUrl](./get-download-room-note-url.md)

# getDownloadRoomNoteUrl

`abstract fun getDownloadRoomNoteUrl(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, noteId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, saveToFiles: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, success: (response: `[`KmeRoomNoteDownloadUrlResponse`](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-download-url-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Getting an url for download note as pdf file

### Parameters

`roomId` - id of a room

`noteId` - id of a note

`saveToFiles` -

`success` - function to handle success result. Contains [KmeRoomNoteDownloadUrlResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-room-note-download-url-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object