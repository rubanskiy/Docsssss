[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeUserApiService](index.md) / [getUserInfo](./get-user-info.md)

# getUserInfo

`@GET("user/getUserInformation") abstract suspend fun getUserInfo(): `[`KmeGetUserInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md)

Getting actual user information

**Return**
[KmeGetUserInfoResponse](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md) object in success case

`@GET("user/getUserInformation") abstract suspend fun getUserInfo(@Query("room_alias") roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`KmeGetUserInfoResponse`](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md)

Getting actual user information by specific room

### Parameters

`roomAlias` - alias of a room

**Return**
[KmeGetUserInfoResponse](../../com.kme.kaltura.kmesdk.rest.response.user/-kme-get-user-info-response/index.md) object in success case

