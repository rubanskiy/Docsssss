[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.rest.service](../index.md) / [KmeRoomRecordingApiService](index.md) / [heckRecordingLicense](./heck-recording-license.md)

# heckRecordingLicense

`@GET("company/CheckRecordingLicenseToCompanyByRoom") abstract suspend fun heckRecordingLicense(@Query("room_id") roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`KmeCheckRecordingLicenseResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-check-recording-license-response/index.md)

Checking recording license for the room

### Parameters

`roomId` - id of a room

**Return**
[KmeCheckRecordingLicenseResponse](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-check-recording-license-response/index.md) object in success case

