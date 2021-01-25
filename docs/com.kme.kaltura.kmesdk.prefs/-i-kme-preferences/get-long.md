[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.prefs](../index.md) / [IKmePreferences](index.md) / [getLong](./get-long.md)

# getLong

`abstract fun getLong(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, defaultValue: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)` = 0L): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)

Getting [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) value from the preferences by key

### Parameters

`key` - preferences key

`defaultValue` - default value in case key is not stored in the preferences

**Return**
stored value if exist, otherwise [defaultValue](get-long.md#com.kme.kaltura.kmesdk.prefs.IKmePreferences$getLong(kotlin.String, kotlin.Long)/defaultValue)

