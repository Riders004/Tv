# Class: NotificationSettings

Defined in: [WAProto/index.d.ts:24527](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24527)

Represents a NotificationSettings.

## Implements

- [`INotificationSettings`](../interfaces/INotificationSettings.md)

## Constructors

### new NotificationSettings()

> **new NotificationSettings**(`properties`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:24533](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24533)

Constructs a new NotificationSettings.

#### Parameters

##### properties?

[`INotificationSettings`](../interfaces/INotificationSettings.md)

Properties to set

#### Returns

[`NotificationSettings`](NotificationSettings.md)

## Properties

### callVibrate

> **callVibrate**: `string`

Defined in: [WAProto/index.d.ts:24551](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24551)

NotificationSettings callVibrate.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`callVibrate`](../interfaces/INotificationSettings.md#callvibrate)

***

### lowPriorityNotifications

> **lowPriorityNotifications**: `boolean`

Defined in: [WAProto/index.d.ts:24545](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24545)

NotificationSettings lowPriorityNotifications.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`lowPriorityNotifications`](../interfaces/INotificationSettings.md#lowprioritynotifications)

***

### messageLight

> **messageLight**: `string`

Defined in: [WAProto/index.d.ts:24542](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24542)

NotificationSettings messageLight.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messageLight`](../interfaces/INotificationSettings.md#messagelight)

***

### messagePopup

> **messagePopup**: `string`

Defined in: [WAProto/index.d.ts:24539](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24539)

NotificationSettings messagePopup.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messagePopup`](../interfaces/INotificationSettings.md#messagepopup)

***

### messageVibrate

> **messageVibrate**: `string`

Defined in: [WAProto/index.d.ts:24536](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24536)

NotificationSettings messageVibrate.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messageVibrate`](../interfaces/INotificationSettings.md#messagevibrate)

***

### reactionsMuted

> **reactionsMuted**: `boolean`

Defined in: [WAProto/index.d.ts:24548](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24548)

NotificationSettings reactionsMuted.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`reactionsMuted`](../interfaces/INotificationSettings.md#reactionsmuted)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24621](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24621)

Converts this NotificationSettings to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:24558](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24558)

Creates a new NotificationSettings instance using the specified properties.

#### Parameters

##### properties?

[`INotificationSettings`](../interfaces/INotificationSettings.md)

Properties to set

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:24584](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24584)

Decodes a NotificationSettings message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:24593](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24593)

Decodes a NotificationSettings message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24566](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24566)

Encodes the specified NotificationSettings message. Does not implicitly [verify](NotificationSettings.md#verify) messages.

#### Parameters

##### message

[`INotificationSettings`](../interfaces/INotificationSettings.md)

NotificationSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24574](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24574)

Encodes the specified NotificationSettings message, length delimited. Does not implicitly [verify](NotificationSettings.md#verify) messages.

#### Parameters

##### message

[`INotificationSettings`](../interfaces/INotificationSettings.md)

NotificationSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:24607](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24607)

Creates a NotificationSettings message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:24615](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24615)

Creates a plain object from a NotificationSettings message. Also converts values to other types if specified.

#### Parameters

##### message

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24600](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24600)

Verifies a NotificationSettings message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
