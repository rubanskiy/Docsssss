[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.adapter](../index.md) / [UserCompaniesAdapter](./index.md)

# UserCompaniesAdapter

`class UserCompaniesAdapter : `[`ArrayAdapter`](https://developer.android.com/reference/android/widget/ArrayAdapter.html)`<KmeUserCompany>`

### Types

| Name | Summary |
|---|---|
| [UserCompanyViewHolder](-user-company-view-holder/index.md) | `inner class UserCompanyViewHolder : ViewHolder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UserCompaniesAdapter(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, inflater: `[`LayoutInflater`](https://developer.android.com/reference/android/view/LayoutInflater.html)` = LayoutInflater.from(context))` |

### Properties

| Name | Summary |
|---|---|
| [onCompanyClick](on-company-click.md) | `var onCompanyClick: (userCompany: KmeUserCompany) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Functions

| Name | Summary |
|---|---|
| [addData](add-data.md) | `fun addData(data: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<KmeUserCompany>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getCount](get-count.md) | `fun getCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getItem](get-item.md) | `fun getItem(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): KmeUserCompany` |
| [getItemId](get-item-id.md) | `fun getItemId(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getView](get-view.md) | `fun getView(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, convertView: `[`View`](https://developer.android.com/reference/android/view/View.html)`?, parent: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`): `[`View`](https://developer.android.com/reference/android/view/View.html) |
