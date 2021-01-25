[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeMetadataController](./index.md)

# IKmeMetadataController

`interface IKmeMetadataController`

An interface for actions related to metadata

### Functions

| Name | Summary |
|---|---|
| [fetchMetadata](fetch-metadata.md) | `abstract fun fetchMetadata(success: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting metadata for global usage |
| [getMetadata](get-metadata.md) | `abstract fun getMetadata(): `[`KmeMetadata`](../../com.kme.kaltura.kmesdk.rest.response.metadata/-kme-metadata/index.md)`?`<br>Getting stored metadata |
| [getTranslation](get-translation.md) | `abstract fun getTranslation(lang: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`GetTranslationsResponse`](../../com.kme.kaltura.kmesdk.rest.response.metadata/-get-translations-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting translations strings for specific language |

### Inheritors

| Name | Summary |
|---|---|
| [KmeMetadataControllerImpl](../../com.kme.kaltura.kmesdk.controller.impl/-kme-metadata-controller-impl/index.md) | `class KmeMetadataControllerImpl : KmeKoinComponent, `[`IKmeMetadataController`](./index.md)<br>An implementation for actions related to metadata |
