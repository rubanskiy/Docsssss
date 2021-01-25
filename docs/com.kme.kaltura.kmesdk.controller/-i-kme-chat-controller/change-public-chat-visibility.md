[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeChatController](index.md) / [changePublicChatVisibility](./change-public-chat-visibility.md)

# changePublicChatVisibility

`abstract fun changePublicChatVisibility(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, value: `[`KmePermissionValue`](../../com.kme.kaltura.kmesdk.ws.message.type.permissions/-kme-permission-value/index.md)`, success: (response: `[`KmeChangeRoomSettingsResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-change-room-settings-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Change visibility of public chat

### Parameters

`roomId` - id of a room

`value` - value flag

`success` - function to handle success result. Contains [KmeChangeRoomSettingsResponse](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-change-room-settings-response/index.md) object

`error` - function to handle error result. Contains [KmeApiException](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md) object