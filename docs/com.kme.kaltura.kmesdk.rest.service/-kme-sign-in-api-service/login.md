[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeSignInApiService](index.md) / [login](./login.md)

# login

`@FormUrlEncoded @POST("signin/login") abstract suspend fun login(@Field("LoginForm[email]") email: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, @Field("LoginForm[password]") password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`KmeLoginResponse`](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-login-response/index.md)

Login user by input data

### Parameters

`email` - email of a user

`password` - password of a user

**Return**
[KmeLoginResponse](../../com.kme.kaltura.kmesdk.rest.response.signin/-kme-login-response/index.md) object in success case

