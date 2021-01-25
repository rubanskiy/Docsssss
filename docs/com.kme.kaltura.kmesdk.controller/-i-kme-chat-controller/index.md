[kmeSdk](../../index.md) / [com.kme.kaltura.kmesdk.controller](../index.md) / [IKmeChatController](./index.md)

# IKmeChatController

`interface IKmeChatController`

An interface for actions related to chat

### Functions

| Name | Summary |
|---|---|
| [changePublicChatVisibility](change-public-chat-visibility.md) | `abstract fun changePublicChatVisibility(roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, value: `[`KmePermissionValue`](../../com.kme.kaltura.kmesdk.ws.message.type.permissions/-kme-permission-value/index.md)`, success: (response: `[`KmeChangeRoomSettingsResponse`](../../com.kme.kaltura.kmesdk.rest.response.room/-kme-change-room-settings-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, error: (exception: `[`KmeApiException`](../../com.kme.kaltura.kmesdk.rest/-kme-api-exception/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Change visibility of public chat |

### Inheritors

| Name | Summary |
|---|---|
| [KmeChatControllerImpl](../../com.kme.kaltura.kmesdk.controller.impl/-kme-chat-controller-impl/index.md) | `class KmeChatControllerImpl : `[`KmeController`](../../com.kme.kaltura.kmesdk.controller.impl/-kme-controller/index.md)`, `[`IKmeChatController`](./index.md)<br>An implementation actions related to chat |
