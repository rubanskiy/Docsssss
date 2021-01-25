[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.content.slides](../index.md) / [KmeSlidesView](./index.md)

# KmeSlidesView

`class KmeSlidesView : ConstraintLayout, `[`IKmeSlidesListener`](../-i-kme-slides-listener/index.md)

An implementation of slides view in the room

### Types

| Name | Summary |
|---|---|
| [Config](-config/index.md) | `class Config` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeSlidesView(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, attrs: `[`AttributeSet`](https://developer.android.com/reference/android/util/AttributeSet.html)`? = null, defStyleAttr: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0)`<br>An implementation of slides view in the room |

### Properties

| Name | Summary |
|---|---|
| [currentSlide](current-slide.md) | `val currentSlide: `[`Slide`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-active-content-module-message/-active-content-payload/-slide/index.md)`?`<br>Getting actual slide |
| [size](size.md) | `val size: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Getting size of slides collection |

### Functions

| Name | Summary |
|---|---|
| [init](init.md) | `fun init(config: `[`Config`](-config/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Initialize function. Setting config |
| [next](next.md) | `fun next(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Asking for the next slide form slides collection |
| [previous](previous.md) | `fun previous(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Asking for the previous slide form slides collection |
| [setSlides](set-slides.md) | `fun setSlides(slides: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Slide`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-active-content-module-message/-active-content-payload/-slide/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Set actual slides |
| [toSlide](to-slide.md) | `fun toSlide(slideNumber: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting slide by position from slides collection |
