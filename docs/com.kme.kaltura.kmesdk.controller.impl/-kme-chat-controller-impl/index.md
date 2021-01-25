[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller.impl](../index.md) / [KmeChatControllerImpl](./index.md)

# KmeChatControllerImpl

`class KmeChatControllerImpl : `[`KmeController`](../-kme-controller/index.md)`, `[`IKmeChatController`](../../com.kme.kaltura.kmesdk.controller/-i-kme-chat-controller/index.md)

An implementation actions related to chat

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KmeChatControllerImpl()`<br>An implementation actions related to chat |

### Functions

| Name | Summary |
|---|---|
| [changePublicChatVisibility](change-public-chat-visibility.md) | `fun changePublicChatVisibility(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, value: `[`KmePermissionValue`](../../com.kme.kaltura.kmesdk.ws.message.type.permissions/-kme-permission-value/index.md)`, success: (response: `[`KmeChangeRoomSettingsResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-change-room-settings-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Change visibility of public chat |
