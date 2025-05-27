# Class: NotificationMessageInfo

Defined in: [WAProto/index.d.ts:24413](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24413)

Represents a NotificationMessageInfo.

## Implements

- [`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

## Constructors

### new NotificationMessageInfo()

> **new NotificationMessageInfo**(`properties`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:24419](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24419)

Constructs a new NotificationMessageInfo.

#### Parameters

##### properties?

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

Properties to set

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:24422](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24422)

NotificationMessageInfo key.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`key`](../interfaces/INotificationMessageInfo.md#key)

***

### message?

> `optional` **message**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:24425](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24425)

NotificationMessageInfo message.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`message`](../interfaces/INotificationMessageInfo.md#message)

***

### messageTimestamp

> **messageTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:24428](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24428)

NotificationMessageInfo messageTimestamp.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`messageTimestamp`](../interfaces/INotificationMessageInfo.md#messagetimestamp)

***

### participant

> **participant**: `string`

Defined in: [WAProto/index.d.ts:24431](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24431)

NotificationMessageInfo participant.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`participant`](../interfaces/INotificationMessageInfo.md#participant)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24501](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24501)

Converts this NotificationMessageInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:24438](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24438)

Creates a new NotificationMessageInfo instance using the specified properties.

#### Parameters

##### properties?

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

Properties to set

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:24464](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24464)

Decodes a NotificationMessageInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:24473](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24473)

Decodes a NotificationMessageInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24446](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24446)

Encodes the specified NotificationMessageInfo message. Does not implicitly [verify](NotificationMessageInfo.md#verify) messages.

#### Parameters

##### message

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

NotificationMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24454](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24454)

Encodes the specified NotificationMessageInfo message, length delimited. Does not implicitly [verify](NotificationMessageInfo.md#verify) messages.

#### Parameters

##### message

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

NotificationMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:24487](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24487)

Creates a NotificationMessageInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:24495](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24495)

Creates a plain object from a NotificationMessageInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24480](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24480)

Verifies a NotificationMessageInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
