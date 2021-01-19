[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.view.activity](../index.md) / [RoomActivity](./index.md)

# RoomActivity

`class RoomActivity : `[`KmeActivity`](../-kme-activity/index.md)

Example of a class comment.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomActivity()`<br>Example of a class comment. |

### Functions

| Name | Summary |
|---|---|
| [onBackPressed](on-back-pressed.md) | `fun onBackPressed(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `fun onCreate(savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Example of a class comment. |
| [onDestroy](on-destroy.md) | `fun onDestroy(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onRequestPermissionsResult](on-request-permissions-result.md) | `fun onRequestPermissionsResult(requestCode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, permissions: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>, grantResults: `[`IntArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [hideHomeButton](../-kme-activity/hide-home-button.md) | `fun hideHomeButton(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onSupportNavigateUp](../-kme-activity/on-support-navigate-up.md) | `open fun onSupportNavigateUp(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setCustomToolbar](../-kme-activity/set-custom-toolbar.md) | `fun setCustomToolbar(toolbar: Toolbar): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [showHomeButton](../-kme-activity/show-home-button.md) | `fun showHomeButton(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toolbarTitle](../-kme-activity/toolbar-title.md) | `fun toolbarTitle(title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [COMPANY_ID_EXTRA](-c-o-m-p-a-n-y_-i-d_-e-x-t-r-a.md) | `const val COMPANY_ID_EXTRA: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [PERMISSIONS](-p-e-r-m-i-s-s-i-o-n-s.md) | `var PERMISSIONS: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [ROOM_ALIAS_EXTRA](-r-o-o-m_-a-l-i-a-s_-e-x-t-r-a.md) | `const val ROOM_ALIAS_EXTRA: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ROOM_ID_EXTRA](-r-o-o-m_-i-d_-e-x-t-r-a.md) | `const val ROOM_ID_EXTRA: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [openRoomActivity](open-room-activity.md) | `fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.openRoomActivity(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.openRoomActivity(roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

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
