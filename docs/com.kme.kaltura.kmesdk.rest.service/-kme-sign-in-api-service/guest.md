[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeSignInApiService](index.md) / [guest](./guest.md)

# guest

`@FormUrlEncoded @POST("signin/guest") abstract suspend fun guest(@Field("Guest[name]") name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, @Field("Guest[email]") email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, @Field("Guest[room_alias]") roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, @Field("room_alias") roomAliasField: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`KmeGuestLoginResponse`](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-guest-login-response/index.md)

Login user by input data and allow to connect to the room

### Parameters

`name` - name of a user

`email` - email of a user

`roomAlias` - alias of a room

`roomAliasField` - alias of a room

**Return**
[KmeGuestLoginResponse](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-guest-login-response/index.md) object in success case

