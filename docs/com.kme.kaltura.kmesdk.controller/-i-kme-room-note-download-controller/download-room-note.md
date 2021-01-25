[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomNoteDownloadController](index.md) / [downloadRoomNote](./download-room-note.md)

# downloadRoomNote

`abstract fun downloadRoomNote(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`Exception`](https://developer.android.com/reference/java/lang/Exception.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Download specific note as pdf file

### Parameters

`name` - name of a note

`url` - url location of a note

`success` - function to handle success result. Contains [KmeGetRoomNotesResponse](../../com.kme.kaltura.kmesdk.rest.response.room.notes/-kme-get-room-notes-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object