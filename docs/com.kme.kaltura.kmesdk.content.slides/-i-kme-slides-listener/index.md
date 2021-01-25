[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.content.slides](../index.md) / [IKmeSlidesListener](./index.md)

# IKmeSlidesListener

`interface IKmeSlidesListener`

An interface for slides in the room

### Properties

| Name | Summary |
|---|---|
| [currentSlide](current-slide.md) | `abstract val currentSlide: `[`Slide`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-active-content-module-message/-active-content-payload/-slide/index.md)`?`<br>Getting actual slide |
| [size](size.md) | `abstract val size: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Getting size of slides collection |

### Functions

| Name | Summary |
|---|---|
| [init](init.md) | `abstract fun init(config: `[`Config`](../-kme-slides-view/-config/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Initialize function. Setting config |
| [next](next.md) | `abstract fun next(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Asking for the next slide form slides collection |
| [previous](previous.md) | `abstract fun previous(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Asking for the previous slide form slides collection |
| [setSlides](set-slides.md) | `abstract fun setSlides(slides: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Slide`](../../com.kme.kaltura.kmesdk.ws.message.module/-kme-active-content-module-message/-active-content-payload/-slide/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Set actual slides |
| [toSlide](to-slide.md) | `abstract fun toSlide(slideNumber: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Getting slide by position from slides collection |

### Inheritors

| Name | Summary |
|---|---|
| [KmeSlidesView](../-kme-slides-view/index.md) | `class KmeSlidesView : ConstraintLayout, `[`IKmeSlidesListener`](./index.md)<br>An implementation of slides view in the room |
