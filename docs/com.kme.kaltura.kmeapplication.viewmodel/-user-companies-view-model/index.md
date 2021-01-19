[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [UserCompaniesViewModel](./index.md)

# UserCompaniesViewModel

`class UserCompaniesViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UserCompaniesViewModel(kmeSdk: KME, appPreferences: `[`IAppPreferences`](../../com.kme.kaltura.kmeapplication.prefs/-i-app-preferences/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [isLoadingLiveData](is-loading-live-data.md) | `val isLoadingLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [userCompaniesErrorLiveData](user-companies-error-live-data.md) | `val userCompaniesErrorLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [userCompaniesLiveData](user-companies-live-data.md) | `val userCompaniesLiveData: LiveData<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeUserCompany>>` |

### Functions

| Name | Summary |
|---|---|
| [fetchUserCompanies](fetch-user-companies.md) | `fun fetchUserCompanies(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
