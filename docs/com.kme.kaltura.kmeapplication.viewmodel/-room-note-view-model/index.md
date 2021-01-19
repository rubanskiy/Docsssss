[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [RoomNoteViewModel](./index.md)

# RoomNoteViewModel

`class RoomNoteViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomNoteViewModel(kmeSdk: KME, gson: Gson)` |

### Properties

| Name | Summary |
|---|---|
| [addToFilesStateLiveData](add-to-files-state-live-data.md) | `val addToFilesStateLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [adminControlsLiveData](admin-controls-live-data.md) | `val adminControlsLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [broadcastNoteLiveData](broadcast-note-live-data.md) | `val broadcastNoteLiveData: LiveData<KmeRoomNote>` |
| [deleteNoteStateLiveData](delete-note-state-live-data.md) | `val deleteNoteStateLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [deletedNoteLiveData](deleted-note-live-data.md) | `val deletedNoteLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [downloadStateLiveData](download-state-live-data.md) | `val downloadStateLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [isLoadingLiveData](is-loading-live-data.md) | `val isLoadingLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [noteTextChangedLiveData](note-text-changed-live-data.md) | `val noteTextChangedLiveData: LiveData<`[`SpannableString`](https://developer.android.com/reference/android/text/SpannableString.html)`>` |
| [openNoteLiveData](open-note-live-data.md) | `val openNoteLiveData: LiveData<KmeRoomNote>` |
| [roomNotesLiveData](room-notes-live-data.md) | `val roomNotesLiveData: LiveData<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeRoomNote>>` |

### Functions

| Name | Summary |
|---|---|
| [addNoteToFiles](add-note-to-files.md) | `fun addNoteToFiles(roomNote: KmeRoomNote): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [broadcastNote](broadcast-note.md) | `fun broadcastNote(roomNote: KmeRoomNote): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [createNote](create-note.md) | `fun createNote(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [deleteNote](delete-note.md) | `fun deleteNote(roomNote: KmeRoomNote): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [downloadNote](download-note.md) | `fun downloadNote(roomNote: KmeRoomNote): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getRoomNotes](get-room-notes.md) | `fun getRoomNotes(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [openNote](open-note.md) | `fun openNote(roomNote: KmeRoomNote): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [renameNote](rename-note.md) | `fun renameNote(noteId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, newName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setNoteContent](set-note-content.md) | `fun setNoteContent(content: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRoomData](set-room-data.md) | `fun setRoomData(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [subscribeToNoteChanges](subscribe-to-note-changes.md) | `fun subscribeToNoteChanges(noteId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, isSubscribe: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
