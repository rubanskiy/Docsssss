[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeRoomRecordingController](./index.md)

# IKmeRoomRecordingController

`interface IKmeRoomRecordingController`

An interface for recording in the room

### Functions

| Name | Summary |
|---|---|
| [checkRecordingLicense](check-recording-license.md) | `abstract fun checkRecordingLicense(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, success: (response: `[`KmeCheckRecordingLicenseResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-check-recording-license-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Checking recording license for the room |

### Inheritors

| Name | Summary |
|---|---|
| [KmeRoomRecordingControllerImpl](../../com.kme.kaltura.kmesdk.controller.impl/-kme-room-recording-controller-impl/index.md) | `class KmeRoomRecordingControllerImpl : `[`KmeController`](../../com.kme.kaltura.kmesdk.controller.impl/-kme-controller/index.md)`, `[`IKmeRoomRecordingController`](./index.md)<br>An implementation for recording in the room |
