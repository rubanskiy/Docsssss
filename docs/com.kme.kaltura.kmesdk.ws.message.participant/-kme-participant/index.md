[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.ws.message.participant](../index.md) / [KmeParticipant](./index.md)

# KmeParticipant

`data class KmeParticipant : `[`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeParticipant(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, regionId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, userType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, avatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, userRole: `[`KmeUserRole`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-user-role/index.md)`? = null, fullName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, regionName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, joinTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, connectionState: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, liveMediaState: `[`KmeMediaDeviceState`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-media-device-state/index.md)`? = null, webcamState: `[`KmeMediaDeviceState`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-media-device-state/index.md)`? = null, micState: `[`KmeMediaDeviceState`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-media-device-state/index.md)`? = null, timeHandRaised: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, lastUnmuteTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, deviceType: `[`KmePlatformType`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-platform-type/index.md)`? = null, browser: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, country: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, city: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, managingServerId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, outOfTabFocus: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null, userPermissions: `[`KmeSettingsV2`](../../com.kme.kaltura.kmesdk.rest.response.room.settings/-kme-settings-v2/index.md)`? = null, isModerator: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?, isCaptioner: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?, lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`? = null, long: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`? = null, isSpeaking: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, isHandRaised: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false)` |

### Properties

| Name | Summary |
|---|---|
| [avatar](avatar.md) | `var avatar: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [browser](browser.md) | `var browser: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [city](city.md) | `var city: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [connectionState](connection-state.md) | `var connectionState: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [country](country.md) | `var country: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [deviceType](device-type.md) | `var deviceType: `[`KmePlatformType`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-platform-type/index.md)`?` |
| [fullName](full-name.md) | `var fullName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [isCaptioner](is-captioner.md) | `var isCaptioner: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [isHandRaised](is-hand-raised.md) | `var isHandRaised: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isModerator](is-moderator.md) | `var isModerator: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [isSpeaking](is-speaking.md) | `var isSpeaking: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [joinTime](join-time.md) | `var joinTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [lastUnmuteTime](last-unmute-time.md) | `var lastUnmuteTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [lat](lat.md) | `var lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?` |
| [liveMediaState](live-media-state.md) | `var liveMediaState: `[`KmeMediaDeviceState`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-media-device-state/index.md)`?` |
| [long](long.md) | `var long: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?` |
| [managingServerId](managing-server-id.md) | `var managingServerId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [micState](mic-state.md) | `var micState: `[`KmeMediaDeviceState`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-media-device-state/index.md)`?` |
| [outOfTabFocus](out-of-tab-focus.md) | `var outOfTabFocus: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |
| [regionId](region-id.md) | `var regionId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [regionName](region-name.md) | `var regionName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [timeHandRaised](time-hand-raised.md) | `var timeHandRaised: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [userId](user-id.md) | `var userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [userPermissions](user-permissions.md) | `var userPermissions: `[`KmeSettingsV2`](../../com.kme.kaltura.kmesdk.rest.response.room.settings/-kme-settings-v2/index.md)`?` |
| [userRole](user-role.md) | `var userRole: `[`KmeUserRole`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-user-role/index.md)`?` |
| [userType](user-type.md) | `var userType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [webcamState](webcam-state.md) | `var webcamState: `[`KmeMediaDeviceState`](../../com.kme.kaltura.kmesdk.ws.message.type/-kme-media-device-state/index.md)`?` |
