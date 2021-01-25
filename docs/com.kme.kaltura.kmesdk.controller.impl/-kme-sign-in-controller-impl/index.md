[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller.impl](../index.md) / [KmeSignInControllerImpl](./index.md)

# KmeSignInControllerImpl

`class KmeSignInControllerImpl : `[`KmeController`](../-kme-controller/index.md)`, `[`IKmeSignInController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-sign-in-controller/index.md)

An implementation for signIn/signUp

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeSignInControllerImpl()`<br>An implementation for signIn/signUp |

### Functions

| Name | Summary |
|---|---|
| [guest](guest.md) | `fun guest(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`KmeGuestLoginResponse`](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-guest-login-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Login user by input data and allow to connect to the room |
| [login](login.md) | `fun login(email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, success: (response: `[`KmeLoginResponse`](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-login-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Login user by input data |
| [logout](logout.md) | `fun logout(success: (response: `[`KmeLogoutResponse`](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-logout-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Logout from actual user |
| [register](register.md) | `fun register(fullName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, forceRegister: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, addToMailingList: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, success: (response: `[`KmeRegisterResponse`](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-register-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Registers new user by input data |

### Companion Object Properties

| Name | Summary |
|---|---|
| [PASS_ENCRYPT_KEY](-p-a-s-s_-e-n-c-r-y-p-t_-k-e-y.md) | `const val PASS_ENCRYPT_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
