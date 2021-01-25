[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomNoteDownloadController](./index.md)

# IKmeRoomNoteDownloadController

`interface IKmeRoomNoteDownloadController`

An interface for download notes

### Functions

| Name | Summary |
|---|---|
| [downloadRoomNote](download-room-note.md) | `abstract fun downloadRoomNote(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`Exception`](https://developer.android.com/reference/java/lang/Exception.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Download specific note as pdf file |

### Inheritors

| Name | Summary |
|---|---|
| [IKmeRoomNotesController](../-i-kme-room-notes-controller/index.md) | `interface IKmeRoomNotesController : `[`IKmeRoomNoteDownloadController`](./index.md)<br>An interface for actions with notes |
