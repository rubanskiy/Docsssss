[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication](../index.md) / [KmeApplication](./index.md)

# KmeApplication

`class KmeApplication : `[`Application`](https://developer.android.com/reference/android/app/Application.html)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeApplication()` |

### Functions

| Name | Summary |
|---|---|
| [onCreate](on-create.md) | `fun onCreate(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [alert](../../com.kme.kaltura.kmeapplication.util.extensions/android.content.-context/alert.md) | `fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.alert(title: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`? = null, message: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`? = null, withPassInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, withTextInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, func: `[`AlertDialogHelper`](../../com.kme.kaltura.kmeapplication.util.extensions/-alert-dialog-helper/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): AlertDialog`<br>`fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.alert(titleResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, messageResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, withPassInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, withTextInput: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, func: `[`AlertDialogHelper`](../../com.kme.kaltura.kmeapplication.util.extensions/-alert-dialog-helper/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): AlertDialog` |
| [radioDialog](../../com.kme.kaltura.kmeapplication.util.extensions/android.content.-context/radio-dialog.md) | `fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.radioDialog(titleResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, messageResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, variants: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, func: `[`AlertDialogHelper`](../../com.kme.kaltura.kmeapplication.util.extensions/-alert-dialog-helper/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): AlertDialog` |
| [showKeyboard](../../com.kme.kaltura.kmeapplication.util.extensions/android.content.-context/show-keyboard.md) | `fun `[`Context`](https://developer.android.com/reference/android/content/Context.html)`.showKeyboard(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
