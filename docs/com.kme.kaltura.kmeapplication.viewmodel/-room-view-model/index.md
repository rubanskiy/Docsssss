[kmeApp](../../index.md) / [com.kme.kaltura.kmeapplication.viewmodel](../index.md) / [RoomViewModel](./index.md)

# RoomViewModel

`class RoomViewModel : ViewModel, IKmeWSConnectionListener`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoomViewModel(kmeSdk: KME)` |

### Properties

| Name | Summary |
|---|---|
| [anyInstructorsIsConnectedLiveData](any-instructors-is-connected-live-data.md) | `val anyInstructorsIsConnectedLiveData: LiveData<KmeRoomInitModuleMessage<AnyInstructorsIsConnectedToRoomPayload>>` |
| [awaitApprovalLiveData](await-approval-live-data.md) | `val awaitApprovalLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [closeConnectionLiveData](close-connection-live-data.md) | `val closeConnectionLiveData: LiveData<KmeRoomInitModuleMessage<CloseWebSocketPayload>?>` |
| [handRaisedLiveData](hand-raised-live-data.md) | `val handRaisedLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [instructorIsOfflineLiveData](instructor-is-offline-live-data.md) | `val instructorIsOfflineLiveData: LiveData<KmeRoomInitModuleMessage<InstructorIsOfflinePayload>?>` |
| [isClosedLiveData](is-closed-live-data.md) | `val isClosedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [isConnectedLiveData](is-connected-live-data.md) | `val isConnectedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [isConnectionFailureLiveData](is-connection-failure-live-data.md) | `val isConnectionFailureLiveData: LiveData<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`?>` |
| [isLoadingLiveData](is-loading-live-data.md) | `val isLoadingLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [joinedRoomLiveData](joined-room-live-data.md) | `val joinedRoomLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [roomHasPasswordLiveData](room-has-password-live-data.md) | `val roomHasPasswordLiveData: LiveData<KmeBannersModuleMessage<BannersPayload>?>` |
| [roomInfoErrorLiveData](room-info-error-live-data.md) | `val roomInfoErrorLiveData: LiveData<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [roomParticipantLimitReachedLiveData](room-participant-limit-reached-live-data.md) | `val roomParticipantLimitReachedLiveData: LiveData<KmeRoomInitModuleMessage<RoomParticipantLimitReachedPayload>?>` |
| [roomPasswordStatusLiveData](room-password-status-live-data.md) | `val roomPasswordStatusLiveData: LiveData<KmeBannersModuleMessage<RoomPasswordStatusReceivedPayload>?>` |
| [roomStateLoadedLiveData](room-state-loaded-live-data.md) | `val roomStateLoadedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [userApprovedLiveData](user-approved-live-data.md) | `val userApprovedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [userRejectedLiveData](user-rejected-live-data.md) | `val userRejectedLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [webRTCServerLiveData](web-r-t-c-server-live-data.md) | `val webRTCServerLiveData: LiveData<`[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)`>` |
| [youModeratorLiveData](you-moderator-live-data.md) | `val youModeratorLiveData: LiveData<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [connect](connect.md) | `fun connect(companyId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, roomAlias: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [endSession](end-session.md) | `fun endSession(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [endSessionForEveryone](end-session-for-everyone.md) | `fun endSessionForEveryone(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isAdmin](is-admin.md) | `fun isAdmin(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isModerator](is-moderator.md) | `fun isModerator(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onCleared](on-cleared.md) | `fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onClosed](on-closed.md) | `fun onClosed(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, reason: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onClosing](on-closing.md) | `fun onClosing(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, reason: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onFailure](on-failure.md) | `fun onFailure(throwable: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onOpen](on-open.md) | `fun onOpen(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [putHandDownByAdmin](put-hand-down-by-admin.md) | `fun putHandDownByAdmin(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [raiseHand](raise-hand.md) | `fun raiseHand(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [submitPassword](submit-password.md) | `fun submitPassword(password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
