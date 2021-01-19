[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.activity](../index.md) / [KmeActivity](./index.md)

# KmeActivity

`abstract class KmeActivity : AppCompatActivity`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeActivity()` |

### Functions

| Name | Summary |
|---|---|
| [hideHomeButton](hide-home-button.md) | `fun hideHomeButton(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onSupportNavigateUp](on-support-navigate-up.md) | `open fun onSupportNavigateUp(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setCustomToolbar](set-custom-toolbar.md) | `fun setCustomToolbar(toolbar: Toolbar): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [showHomeButton](show-home-button.md) | `fun showHomeButton(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toolbarTitle](toolbar-title.md) | `fun toolbarTitle(title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [addFragment](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/add-fragment.md) | `fun AppCompatActivity.addFragment(fragment: Fragment, frameId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun AppCompatActivity.addFragment(fragment: Fragment, frameId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, addToStack: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [alert](../../com.kme.kaltura.kmeapplication.util.extensions/android.content.-context/alert.md) | `fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.alert(title: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`? = null, message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`? = null, withPassInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, withTextInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, func: `[`AlertDialogHelper`](../../com.kme.kaltura.kmeapplication.util.extensions/-alert-dialog-helper/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): AlertDialog`<br>`fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.alert(titleResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, messageResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, withPassInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, withTextInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, func: `[`AlertDialogHelper`](../../com.kme.kaltura.kmeapplication.util.extensions/-alert-dialog-helper/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): AlertDialog` |
| [getCurrentFragment](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/get-current-fragment.md) | `fun AppCompatActivity.getCurrentFragment(): Fragment?` |
| [getFragmentById](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/get-fragment-by-id.md) | `fun AppCompatActivity.getFragmentById(frameId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Fragment?` |
| [getFragmentByTag](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/get-fragment-by-tag.md) | `fun AppCompatActivity.getFragmentByTag(tag: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Fragment?` |
| [hideKeyboard](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/hide-keyboard.md) | `fun AppCompatActivity.hideKeyboard(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [popBackStack](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/pop-back-stack.md) | `fun AppCompatActivity.popBackStack(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [popBackStackInclusive](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/pop-back-stack-inclusive.md) | `fun AppCompatActivity.popBackStackInclusive(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [radioDialog](../../com.kme.kaltura.kmeapplication.util.extensions/android.content.-context/radio-dialog.md) | `fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.radioDialog(titleResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, messageResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, variants: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, func: `[`AlertDialogHelper`](../../com.kme.kaltura.kmeapplication.util.extensions/-alert-dialog-helper/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): AlertDialog` |
| [removeFragment](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/remove-fragment.md) | `fun AppCompatActivity.removeFragment(fragment: Fragment): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun AppCompatActivity.removeFragment(tag: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [replaceFragment](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.appcompat.app.-app-compat-activity/replace-fragment.md) | `fun AppCompatActivity.replaceFragment(fragment: Fragment, frameId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun AppCompatActivity.replaceFragment(fragment: Fragment, frameId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, addToStack: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun AppCompatActivity.replaceFragment(fragment: Fragment, frameId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, addToStack: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, clearBackStack: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [showKeyboard](../../com.kme.kaltura.kmeapplication.util.extensions/android.content.-context/show-keyboard.md) | `fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.showKeyboard(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [RoomActivity](../-room-activity/index.md) | `class RoomActivity : `[`KmeActivity`](./index.md)<br>Example of a class comment. |
| [RoomInfoActivity](../-room-info-activity/index.md) | `class RoomInfoActivity : `[`KmeActivity`](./index.md)`, OnRefreshListener` |
| [RoomsListActivity](../-rooms-list-activity/index.md) | `class RoomsListActivity : `[`KmeActivity`](./index.md)`, OnRefreshListener` |
