# Class: PollVoteMessage

Defined in: [WAProto/index.d.ts:20625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20625)

Represents a PollVoteMessage.

## Implements

- [`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

## Constructors

### new PollVoteMessage()

> **new PollVoteMessage**(`properties`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:20631](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20631)

Constructs a new PollVoteMessage.

#### Parameters

##### properties?

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

Properties to set

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

## Properties

### selectedOptions

> **selectedOptions**: `Uint8Array`\<`ArrayBufferLike`\>[]

Defined in: [WAProto/index.d.ts:20634](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20634)

PollVoteMessage selectedOptions.

#### Implementation of

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md).[`selectedOptions`](../interfaces/IPollVoteMessage.md#selectedoptions)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20704](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20704)

Converts this PollVoteMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:20641](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20641)

Creates a new PollVoteMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

Properties to set

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:20667](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20667)

Decodes a PollVoteMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:20676](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20676)

Decodes a PollVoteMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20649](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20649)

Encodes the specified PollVoteMessage message. Does not implicitly [verify](PollVoteMessage.md#verify) messages.

#### Parameters

##### message

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

PollVoteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20657](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20657)

Encodes the specified PollVoteMessage message, length delimited. Does not implicitly [verify](PollVoteMessage.md#verify) messages.

#### Parameters

##### message

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

PollVoteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:20690](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20690)

Creates a PollVoteMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20698](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20698)

Creates a plain object from a PollVoteMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20683](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20683)

Verifies a PollVoteMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
