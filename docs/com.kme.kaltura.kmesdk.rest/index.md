[kmeSdk](../index.md) / [com.kme.kaltura.kmesdk.rest](./index.md)

## Package com.kme.kaltura.kmesdk.rest

### Types

| Name | Summary |
|---|---|
| [KmeCookieJar](-kme-cookie-jar/index.md) | `class KmeCookieJar : CookieJar`<br>Provides **policy** and **persistence** for HTTP cookies. |
| [KmeIntToBooleanTypeAdapter](-kme-int-to-boolean-type-adapter/index.md) | `class KmeIntToBooleanTypeAdapter : JsonDeserializer<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [KmeStringToBooleanTypeAdapter](-kme-string-to-boolean-type-adapter/index.md) | `class KmeStringToBooleanTypeAdapter : JsonDeserializer<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |

### Exceptions

| Name | Summary |
|---|---|
| [KmeApiException](-kme-api-exception/index.md) | `sealed class KmeApiException : `[`Exception`](https://developer.android.com/reference/java/lang/Exception.html)<br>Main REST exceptions class. Indicates an error produced by REST response handling |

### Functions

| Name | Summary |
|---|---|
| [downloadFile](download-file.md) | `suspend fun downloadFile(call: suspend () -> ResponseBody?, target: `[`OutputStream`](https://developer.android.com/reference/java/io/OutputStream.html)`, success: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`Exception`](https://developer.android.com/reference/java/lang/Exception.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): <ERROR CLASS>`<br>Main REST function. Download files from the server |
| [safeApiCall](safe-api-call.md) | `suspend fun <T> safeApiCall(call: suspend () -> `[`T`](safe-api-call.md#T)`, success: (response: `[`T`](safe-api-call.md#T)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Main REST function. Sending requests and handle responses |
