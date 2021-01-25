[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../index.md) / [KmeRoomNotesMessage](./index.md)

# KmeRoomNotesMessage

`class KmeRoomNotesMessage<T : `[`NotesPayload`](-notes-payload/index.md)`> : `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<`[`T`](index.md#T)`>`

### Types

| Name | Summary |
|---|---|
| [CreateNotePayload](-create-note-payload/index.md) | `data class CreateNotePayload : `[`NotesPayload`](-notes-payload/index.md) |
| [NewNote](-new-note/index.md) | `data class NewNote` |
| [NewNoteWrapper](-new-note-wrapper/index.md) | `data class NewNoteWrapper` |
| [NoteBlocks](-note-blocks/index.md) | `data class NoteBlocks` |
| [NoteEditBlock](-note-edit-block/index.md) | `data class NoteEditBlock` |
| [NoteEditDelta](-note-edit-delta/index.md) | `data class NoteEditDelta` |
| [NoteEditKeyValueContent](-note-edit-key-value-content/index.md) | `data class NoteEditKeyValueContent` |
| [NoteEditor](-note-editor/index.md) | `data class NoteEditor` |
| [NoteEventData](-note-event-data/index.md) | `data class NoteEventData` |
| [NoteInlineStyle](-note-inline-style/index.md) | `data class NoteInlineStyle` |
| [NotePayload](-note-payload/index.md) | `data class NotePayload : `[`NotesPayload`](-notes-payload/index.md) |
| [NotesPayload](-notes-payload/index.md) | `class NotesPayload : `[`Payload`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/-payload/index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeRoomNotesMessage()` |

### Inherited Properties

| Name | Summary |
|---|---|
| [constraint](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/constraint.md) | `var constraint: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`KmeConstraint`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-constraint/index.md)`>?` |
| [module](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/module.md) | `var module: `[`KmeMessageModule`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message-module/index.md)`?` |
| [name](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/name.md) | `var name: `[`KmeMessageEvent`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message-event/index.md)`?` |
| [payload](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/payload.md) | `var payload: `[`T`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md#T)`?` |
| [type](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/type.md) | `var type: `[`KmeMessageEventType`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message-event-type/index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [toType](../../com.kme.kaltura.kmesdk/to-type.md) | `fun <T> `[`KmeMessage`](../../com.kme.kaltura.kmesdk.ws.message/-kme-message/index.md)`<*>.toType(): `[`T`](../../com.kme.kaltura.kmesdk/to-type.md#T)`?` |
