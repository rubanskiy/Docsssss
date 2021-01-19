[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.util](../index.md) / [LiveEvent](./index.md)

# LiveEvent

`class LiveEvent<T> : MediatorLiveData<`[`T`](index.md#T)`>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LiveEvent()` |

### Functions

| Name | Summary |
|---|---|
| [call](call.md) | `fun call(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Used for cases where T is Void, to make calls cleaner. |
| [observe](observe.md) | `fun observe(owner: LifecycleOwner, observer: Observer<in `[`T`](index.md#T)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [removeObserver](remove-observer.md) | `fun removeObserver(observer: Observer<in `[`T`](index.md#T)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [removeObservers](remove-observers.md) | `fun removeObservers(owner: LifecycleOwner): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setValue](set-value.md) | `fun setValue(t: `[`T`](index.md#T)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [observeOnce](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.lifecycle.-live-data/observe-once.md) | `fun <T> LiveData<`[`T`](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.lifecycle.-live-data/observe-once.md#T)`>.observeOnce(lifecycleOwner: LifecycleOwner, observer: Observer<`[`T`](../../com.kme.kaltura.kmeapplication.util.extensions/androidx.lifecycle.-live-data/observe-once.md#T)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toSingleEvent](../androidx.lifecycle.-live-data/to-single-event.md) | `fun <T> LiveData<`[`T`](../androidx.lifecycle.-live-data/to-single-event.md#T)`>.toSingleEvent(): LiveData<`[`T`](../androidx.lifecycle.-live-data/to-single-event.md#T)`>` |
