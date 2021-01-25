[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws](../index.md) / [IKmeWSConnectionListener](./index.md)

# IKmeWSConnectionListener

`interface IKmeWSConnectionListener`

An interface for socket connection events

### Functions

| Name | Summary |
|---|---|
| [onClosed](on-closed.md) | `abstract fun onClosed(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, reason: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Event about socket connection closed |
| [onClosing](on-closing.md) | `abstract fun onClosing(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, reason: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Event about socket connection closing |
| [onFailure](on-failure.md) | `abstract fun onFailure(throwable: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Event about socket failure |
| [onOpen](on-open.md) | `abstract fun onOpen(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Event about socket connection opened |
