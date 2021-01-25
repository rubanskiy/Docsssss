[kmeSdk](../../../index.md) / [com.kme.kaltura.kmesdk.ws.message.module](../../index.md) / [KmeRoomSettingsModuleMessage](../index.md) / [RoomSettingsChangedPayload](./index.md)

# RoomSettingsChangedPayload

`data class RoomSettingsChangedPayload : `[`SettingsPayload`](../-settings-payload/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomSettingsChangedPayload(userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, roomSettingValue: `[`KmePermissionValue`](../../../com.kme.kaltura.kmesdk.ws.message.type.permissions/-kme-permission-value/index.md)`? = null, changedRoomSetting: `[`KmePermissionKey`](../../../com.kme.kaltura.kmesdk.ws.message.type.permissions/-kme-permission-key/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [changedRoomSetting](changed-room-setting.md) | `var changedRoomSetting: `[`KmePermissionKey`](../../../com.kme.kaltura.kmesdk.ws.message.type.permissions/-kme-permission-key/index.md)`?` |
| [roomId](room-id.md) | `var roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [roomSettingValue](room-setting-value.md) | `var roomSettingValue: `[`KmePermissionValue`](../../../com.kme.kaltura.kmesdk.ws.message.type.permissions/-kme-permission-value/index.md)`?` |
| [userId](user-id.md) | `var userId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
