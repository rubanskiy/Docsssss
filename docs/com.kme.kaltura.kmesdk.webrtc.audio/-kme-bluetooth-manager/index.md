[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.audio](../index.md) / [KmeBluetoothManager](./index.md)

# KmeBluetoothManager

`class KmeBluetoothManager`

An implementation for handling bluetooth audio device switches

### Types

| Name | Summary |
|---|---|
| [BluetoothHeadsetBroadcastReceiver](-bluetooth-headset-broadcast-receiver/index.md) | `inner class BluetoothHeadsetBroadcastReceiver : `[`BroadcastReceiver`](https://developer.android.com/reference/android/content/BroadcastReceiver.html)<br>Callbacks from the system about changing [BluetoothHeadset](https://developer.android.com/reference/android/bluetooth/BluetoothHeadset.html) state |
| [BluetoothServiceListener](-bluetooth-service-listener/index.md) | `inner class BluetoothServiceListener : `[`ServiceListener`](https://developer.android.com/reference/android/bluetooth/BluetoothProfile/ServiceListener.html)<br>Callbacks from the system about plugging in and out for bluetooth devices |
| [State](-state/index.md) | `enum class State` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeBluetoothManager(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, kmeAudioManager: `[`IKmeAudioManager`](../-i-kme-audio-manager/index.md)`, audioManager: `[`AudioManager`](https://developer.android.com/reference/android/media/AudioManager.html)`)`<br>An implementation for handling bluetooth audio device switches |

### Functions

| Name | Summary |
|---|---|
| [getState](get-state.md) | `fun getState(): `[`State`](-state/index.md)`?` |
| [start](start.md) | `fun start(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Start listen for bluetooth devices |
| [startScoAudio](start-sco-audio.md) | `fun startScoAudio(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Start SCO |
| [stop](stop.md) | `fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Stop listen for bluetooth devices |
| [stopScoAudio](stop-sco-audio.md) | `fun stopScoAudio(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Stop SCO |
| [updateDevice](update-device.md) | `fun updateDevice(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Update available bluetooth devices |
