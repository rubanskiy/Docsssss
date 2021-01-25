[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeUserController](./index.md)

# IKmeUserController

`interface IKmeUserController`

An interface for actual user information details

### Functions

| Name | Summary |
|---|---|
| [getCurrentParticipant](get-current-participant.md) | `abstract fun getCurrentParticipant(): `[`KmeParticipant`](../../com.kme.kaltura.kmesdk.ws.message.participant/-kme-participant/index.md)`?`<br>Getting stored user information in the room |
| [getCurrentUserInfo](get-current-user-info.md) | `abstract fun getCurrentUserInfo(): `[`KmeUserInfoData`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-user-info-data/index.md)`?`<br>Getting stored user information |
| [getUserInformation](get-user-information.md) | `abstract fun getUserInformation(success: (response: `[`KmeGetUserInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting actual user information`abstract fun getUserInformation(roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`KmeGetUserInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting actual user information for specific room by alias |
| [isAdminFor](is-admin-for.md) | `abstract fun isAdminFor(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks is actual user has admin permissions for specific company |
| [isLoggedIn](is-logged-in.md) | `abstract fun isLoggedIn(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks is actual user is logged and access token exist |
| [isModerator](is-moderator.md) | `abstract fun isModerator(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks is actual user has moderator permissions |
| [logout](logout.md) | `abstract fun logout(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Removes actual user information |
| [updateParticipant](update-participant.md) | `abstract fun updateParticipant(participant: `[`KmeParticipant`](../../com.kme.kaltura.kmesdk.ws.message.participant/-kme-participant/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Updates actual user info in the room |

### Inheritors

| Name | Summary |
|---|---|
| [KmeUserControllerImpl](../../com.kme.kaltura.kmesdk.controller.impl/-kme-user-controller-impl/index.md) | `class KmeUserControllerImpl : `[`KmeController`](../../com.kme.kaltura.kmesdk.controller.impl/-kme-controller/index.md)`, `[`IKmeUserController`](./index.md)<br>An implementation for actual user information details |
