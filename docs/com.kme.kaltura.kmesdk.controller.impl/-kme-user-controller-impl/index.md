[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller.impl](../index.md) / [KmeUserControllerImpl](./index.md)

# KmeUserControllerImpl

`class KmeUserControllerImpl : `[`KmeController`](../-kme-controller/index.md)`, `[`IKmeUserController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-user-controller/index.md)

An implementation for actual user information details

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeUserControllerImpl()`<br>An implementation for actual user information details |

### Functions

| Name | Summary |
|---|---|
| [getCurrentParticipant](get-current-participant.md) | `fun getCurrentParticipant(): `[`KmeParticipant`](../../com.kme.kaltura.kmesdk.ws.message.participant/-kme-participant/index.md)`?`<br>Getting stored user information in the room |
| [getCurrentUserInfo](get-current-user-info.md) | `fun getCurrentUserInfo(): `[`KmeUserInfoData`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-user-info-data/index.md)`?`<br>Getting stored user information |
| [getUserInformation](get-user-information.md) | `fun getUserInformation(success: (response: `[`KmeGetUserInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting actual user information`fun getUserInformation(roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`KmeGetUserInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting actual user information for specific room by alias |
| [isAdminFor](is-admin-for.md) | `fun isAdminFor(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks is actual user has admin permissions for specific company |
| [isLoggedIn](is-logged-in.md) | `fun isLoggedIn(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks is actual user is logged and access token exist |
| [isModerator](is-moderator.md) | `fun isModerator(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks is actual user has moderator permissions |
| [logout](logout.md) | `fun logout(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Removes actual user information |
| [updateParticipant](update-participant.md) | `fun updateParticipant(participant: `[`KmeParticipant`](../../com.kme.kaltura.kmesdk.ws.message.participant/-kme-participant/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Updates actual user info in the room |
