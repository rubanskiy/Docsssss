[kmeSdk](../../../index.md) / [com.kme.kaltura.kmesdk.rest](../../index.md) / [KmeApiException](../index.md) / [HttpException](./index.md)

# HttpException

`open class HttpException : `[`KmeApiException`](../index.md)

### Exceptions

| Name | Summary |
|---|---|
| [ClientException](-client-exception/index.md) | `class ClientException : `[`HttpException`](./index.md) |
| [ServerException](-server-exception/index.md) | `class ServerException : `[`HttpException`](./index.md) |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HttpException(message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, errorCode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, cause: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [errorCode](error-code.md) | `val errorCode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Inherited Properties

| Name | Summary |
|---|---|
| [message](../message.md) | `open val message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |

### Inheritors

| Name | Summary |
|---|---|
| [ClientException](-client-exception/index.md) | `class ClientException : `[`HttpException`](./index.md) |
| [ServerException](-server-exception/index.md) | `class ServerException : `[`HttpException`](./index.md) |
