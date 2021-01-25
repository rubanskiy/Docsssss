[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeAudioController](./index.md)

# IKmeAudioController

`interface IKmeAudioController`

An interface for handling audio in the room

### Functions

| Name | Summary |
|---|---|
| [getAvailableAudioDevices](get-available-audio-devices.md) | `abstract fun getAvailableAudioDevices(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`?>`<br>Getting set of available audio devices |
| [getSelectedAudioDevice](get-selected-audio-device.md) | `abstract fun getSelectedAudioDevice(): `[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`?`<br>Getting last selected audio device |
| [setAudioDevice](set-audio-device.md) | `abstract fun setAudioDevice(device: `[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Change current audio device |
| [setDefaultAudioDevice](set-default-audio-device.md) | `abstract fun setDefaultAudioDevice(device: `[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting default audio device |
| [setListener](set-listener.md) | `abstract fun setListener(listener: `[`AudioManagerListener`](../../com.kme.kaltura.kmesdk.webrtc.audio/-audio-manager-listener/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Listener for detecting audio route changes |
| [start](start.md) | `abstract fun start(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Starting audio manager |
| [stop](stop.md) | `abstract fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Stopping use audio |

### Inheritors

| Name | Summary |
|---|---|
| [KmeAudioControllerImpl](../../com.kme.kaltura.kmesdk.controller.impl/-kme-audio-controller-impl/index.md) | `class KmeAudioControllerImpl : `[`KmeController`](../../com.kme.kaltura.kmesdk.controller.impl/-kme-controller/index.md)`, `[`IKmeAudioController`](./index.md)<br>An implementation for handling audio in the room |
