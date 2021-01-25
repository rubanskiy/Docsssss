[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest](../index.md) / [KmeCookieJar](./index.md)

# KmeCookieJar

`class KmeCookieJar : CookieJar`

Provides **policy** and **persistence** for HTTP cookies.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeCookieJar(prefs: `[`IKmePreferences`](../../com.kme.kaltura.kmesdk.prefs/-i-kme-preferences/index.md)`)`<br>Provides **policy** and **persistence** for HTTP cookies. |

### Functions

| Name | Summary |
|---|---|
| [loadForRequest](load-for-request.md) | `fun loadForRequest(url: HttpUrl): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<Cookie>`<br>Load cookies from the jar for an HTTP request to [url](load-for-request.md#com.kme.kaltura.kmesdk.rest.KmeCookieJar$loadForRequest(okhttp3.HttpUrl)/url). This method returns a possibly empty list of cookies for the network request. |
| [saveFromResponse](save-from-response.md) | `fun saveFromResponse(url: HttpUrl, cookieList: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<Cookie>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Save cookies only from metadata response |
