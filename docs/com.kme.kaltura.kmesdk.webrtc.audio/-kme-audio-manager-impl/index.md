[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.audio](../index.md) / [KmeAudioManagerImpl](./index.md)

# KmeAudioManagerImpl

`class KmeAudioManagerImpl : `[`IKmeAudioManager`](../-i-kme-audio-manager/index.md)

An implementation for handling audio devices in the room

### Types

| Name | Summary |
|---|---|
| [AudioManagerState](-audio-manager-state/index.md) | `enum class AudioManagerState` |
| [WiredHeadsetReceiver](-wired-headset-receiver/index.md) | `inner class WiredHeadsetReceiver : `[`BroadcastReceiver`](https://developer.android.com/reference/android/content/BroadcastReceiver.html)<br>Callbacks from the system about plugging in and out for wired headset devices |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeAudioManagerImpl(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`)`<br>An implementation for handling audio devices in the room |

### Functions

| Name | Summary |
|---|---|
| [getAvailableAudioDevices](get-available-audio-devices.md) | `fun getAvailableAudioDevices(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`KmeAudioDevice`](../-kme-audio-device/index.md)`?>`<br>Getting set of available audio devices |
| [getSelectedAudioDevice](get-selected-audio-device.md) | `fun getSelectedAudioDevice(): `[`KmeAudioDevice`](../-kme-audio-device/index.md)<br>Getting last selected audio device |
| [setAudioDevice](set-audio-device.md) | `fun setAudioDevice(device: `[`KmeAudioDevice`](../-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Change current audio device |
| [setDefaultAudioDevice](set-default-audio-device.md) | `fun setDefaultAudioDevice(device: `[`KmeAudioDevice`](../-kme-audio-device/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setting default audio device |
| [setListener](set-listener.md) | `fun setListener(listener: `[`AudioManagerListener`](../-audio-manager-listener/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Listener for detecting audio route changes |
| [start](start.md) | `fun start(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Starting audio manager |
| [stop](stop.md) | `fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Stopping use audio |
| [updateAudioDeviceState](update-audio-device-state.md) | `fun updateAudioDeviceState(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Detect all available devices and auto switch to most important for now |
