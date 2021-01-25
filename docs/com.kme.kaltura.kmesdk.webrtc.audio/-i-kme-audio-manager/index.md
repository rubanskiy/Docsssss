[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.audio](../index.md) / [IKmeAudioManager](./index.md)

# IKmeAudioManager

`interface IKmeAudioManager`

An interface for handling audio devices in the room

### Functions

| Name | Summary |
|---|---|
| [getAvailableAudioDevices](get-available-audio-devices.md) | `abstract fun getAvailableAudioDevices(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`KmeAudioDevice`](../-kme-audio-device/index.md)`?>`<br>Getting set of available audio devices |
| [getSelectedAudioDevice](get-selected-audio-device.md) | `abstract fun getSelectedAudioDevice(): `[`KmeAudioDevice`](../-kme-audio-device/index.md)`?`<br>Getting last selected audio device |
| [setAudioDevice](set-audio-device.md) | `abstract fun setAudioDevice(device: `[`KmeAudioDevice`](../-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Change current audio device |
| [setDefaultAudioDevice](set-default-audio-device.md) | `abstract fun setDefaultAudioDevice(device: `[`KmeAudioDevice`](../-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting default audio device |
| [setListener](set-listener.md) | `abstract fun setListener(listener: `[`AudioManagerListener`](../-audio-manager-listener/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Listener for detecting audio route changes |
| [start](start.md) | `abstract fun start(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Starting audio manager |
| [stop](stop.md) | `abstract fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Stopping use audio |
| [updateAudioDeviceState](update-audio-device-state.md) | `abstract fun updateAudioDeviceState(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Detect all available devices and auto switch to most important for now |

### Inheritors

| Name | Summary |
|---|---|
| [KmeAudioManagerImpl](../-kme-audio-manager-impl/index.md) | `class KmeAudioManagerImpl : `[`IKmeAudioManager`](./index.md)<br>An implementation for handling audio devices in the room |
