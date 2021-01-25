[kmeSdk](../index.md) / [com.kme.kaltura.kmesdk.rest](index.md) / [safeApiCall](./safe-api-call.md)

# safeApiCall

`suspend fun <T> safeApiCall(call: suspend () -> `[`T`](safe-api-call.md#T)`, success: (response: `[`T`](safe-api-call.md#T)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Main REST function. Sending requests and handle responses

