[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [SignInViewModel](./index.md)

# SignInViewModel

`class SignInViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SignInViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [guestLoginResponseLiveData](guest-login-response-live-data.md) | `val guestLoginResponseLiveData: LiveData<KmeGuestLoginData>` |
| [isLoadingLiveData](is-loading-live-data.md) | `val isLoadingLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [loginErrorLiveData](login-error-live-data.md) | `val loginErrorLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [loginResponseLiveData](login-response-live-data.md) | `val loginResponseLiveData: LiveData<KmeLoginData>` |

### Functions

| Name | Summary |
|---|---|
| [guest](guest.md) | `fun guest(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [login](login.md) | `fun login(email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
