[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.webrtc.stats](../index.md) / [KmeSoundAmplitudeListener](./index.md)

# KmeSoundAmplitudeListener

`interface KmeSoundAmplitudeListener`

An interface for measure amplitude of actual p2p connection

### Functions

| Name | Summary |
|---|---|
| [onAmplitudeMeasured](on-amplitude-measured.md) | `abstract fun onAmplitudeMeasured(bringToFront: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, amplitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Fired once sound amplitude measured |

### Inheritors

| Name | Summary |
|---|---|
| [KmePeerConnectionImpl](../../com.kme.kaltura.kmesdk.webrtc.peerconnection.impl/-kme-peer-connection-impl/index.md) | `class KmePeerConnectionImpl : `[`IKmePeerConnection`](../../com.kme.kaltura.kmesdk.webrtc.peerconnection/-i-kme-peer-connection/index.md)`, `[`KmeSoundAmplitudeListener`](./index.md)<br>An implementation actions under WebRTC peer connection object |
