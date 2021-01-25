[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk](../index.md) / [KME](./index.md)

# KME

`class KME : KmeKoinComponent`

Main class for KME SDK.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KME()`<br>Main class for KME SDK. |

### Properties

| Name | Summary |
|---|---|
| [audioController](audio-controller.md) | `val audioController: `[`IKmeAudioController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-audio-controller/index.md) |
| [chatController](chat-controller.md) | `val chatController: `[`IKmeChatController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-chat-controller/index.md) |
| [isSDKInitialized](is-s-d-k-initialized.md) | `var isSDKInitialized: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [roomController](room-controller.md) | `val roomController: `[`IKmeRoomController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-room-controller/index.md) |
| [roomNotesController](room-notes-controller.md) | `val roomNotesController: `[`IKmeRoomNotesController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-room-notes-controller/index.md) |
| [roomRecordingController](room-recording-controller.md) | `val roomRecordingController: `[`IKmeRoomRecordingController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-room-recording-controller/index.md) |
| [signInController](sign-in-controller.md) | `val signInController: `[`IKmeSignInController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-sign-in-controller/index.md) |
| [userController](user-controller.md) | `val userController: `[`IKmeUserController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-user-controller/index.md) |

### Functions

| Name | Summary |
|---|---|
| [getCookies](get-cookies.md) | `fun getCookies(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getFilesUrl](get-files-url.md) | `fun getFilesUrl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [initSDK](init-s-d-k.md) | `fun initSDK(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, success: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Initialization function. Initializes all needed controllers and modules. In the same place - fetching metadata from the server to use it in future REST API calls. |

### Companion Object Functions

| Name | Summary |
|---|---|
| [getInstance](get-instance.md) | `fun getInstance(): `[`KME`](./index.md)<br>Instantiate a KME singleton |
