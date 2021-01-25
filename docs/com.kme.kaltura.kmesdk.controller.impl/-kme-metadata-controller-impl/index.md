[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller.impl](../index.md) / [KmeMetadataControllerImpl](./index.md)

# KmeMetadataControllerImpl

`class KmeMetadataControllerImpl : KmeKoinComponent, `[`IKmeMetadataController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-metadata-controller/index.md)

An implementation for actions related to metadata

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeMetadataControllerImpl()`<br>An implementation for actions related to metadata |

### Functions

| Name | Summary |
|---|---|
| [fetchMetadata](fetch-metadata.md) | `fun fetchMetadata(success: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting metadata for global usage |
| [getMetadata](get-metadata.md) | `fun getMetadata(): `[`KmeMetadata`](../../com.kme.kaltura.kmesdk.rest.response.metadata/-kme-metadata/index.md)`?`<br>Getting stored metadata |
| [getTranslation](get-translation.md) | `fun getTranslation(lang: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`GetTranslationsResponse`](../../com.kme.kaltura.kmesdk.rest.response.metadata/-get-translations-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting translations strings for specific language |
