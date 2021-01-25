[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller.impl](../index.md) / [KmeAudioControllerImpl](./index.md)

# KmeAudioControllerImpl

`class KmeAudioControllerImpl : `[`KmeController`](../-kme-controller/index.md)`, `[`IKmeAudioController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-audio-controller/index.md)

An implementation for handling audio in the room

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeAudioControllerImpl()`<br>An implementation for handling audio in the room |

### Functions

| Name | Summary |
|---|---|
| [getAvailableAudioDevices](get-available-audio-devices.md) | `fun getAvailableAudioDevices(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`?>`<br>Getting set of available audio devices |
| [getSelectedAudioDevice](get-selected-audio-device.md) | `fun getSelectedAudioDevice(): `[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`?`<br>Getting last selected audio device |
| [setAudioDevice](set-audio-device.md) | `fun setAudioDevice(device: `[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Change current audio device |
| [setDefaultAudioDevice](set-default-audio-device.md) | `fun setDefaultAudioDevice(device: `[`KmeAudioDevice`](../../com.kme.kaltura.kmesdk.webrtc.audio/-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting default audio device |
| [setListener](set-listener.md) | `fun setListener(listener: `[`AudioManagerListener`](../../com.kme.kaltura.kmesdk.webrtc.audio/-audio-manager-listener/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Listener for detecting audio route changes |
| [start](start.md) | `fun start(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Starting audio manager |
| [stop](stop.md) | `fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Stopping use audio |
