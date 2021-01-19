[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [RoomsListViewModel](./index.md)

# RoomsListViewModel

`class RoomsListViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomsListViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [isLoadingLiveData](is-loading-live-data.md) | `val isLoadingLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [openRoomByLinkErrorLiveData](open-room-by-link-error-live-data.md) | `val openRoomByLinkErrorLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [openRoomByLinkLiveData](open-room-by-link-live-data.md) | `val openRoomByLinkLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [roomsListErrorLiveData](rooms-list-error-live-data.md) | `val roomsListErrorLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [roomsListLiveData](rooms-list-live-data.md) | `val roomsListLiveData: LiveData<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeBaseRoom>>` |
| [selectedCompanyLiveData](selected-company-live-data.md) | `val selectedCompanyLiveData: LiveData<KmeUserCompany>` |
| [userCompaniesErrorLiveData](user-companies-error-live-data.md) | `val userCompaniesErrorLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [userCompaniesLiveData](user-companies-live-data.md) | `val userCompaniesLiveData: LiveData<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeUserCompany>>` |

### Functions

| Name | Summary |
|---|---|
| [fetchRoomsList](fetch-rooms-list.md) | `fun fetchRoomsList(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [fetchUserCompanies](fetch-user-companies.md) | `fun fetchUserCompanies(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [logout](logout.md) | `fun logout(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [openRoomByLink](open-room-by-link.md) | `fun openRoomByLink(link: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [selectCompany](select-company.md) | `fun selectCompany(company: KmeUserCompany): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
