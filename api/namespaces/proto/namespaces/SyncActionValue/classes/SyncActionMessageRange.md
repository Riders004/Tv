# Class: SyncActionMessageRange

Defined in: [WAProto/index.d.ts:33913](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33913)

Represents a SyncActionMessageRange.

## Implements

- [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

## Constructors

### new SyncActionMessageRange()

> **new SyncActionMessageRange**(`properties`?): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:33919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33919)

Constructs a new SyncActionMessageRange.

#### Parameters

##### properties?

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Properties to set

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

## Properties

### lastMessageTimestamp

> **lastMessageTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:33922](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33922)

SyncActionMessageRange lastMessageTimestamp.

#### Implementation of

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md).[`lastMessageTimestamp`](../interfaces/ISyncActionMessageRange.md#lastmessagetimestamp)

***

### lastSystemMessageTimestamp

> **lastSystemMessageTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:33925](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33925)

SyncActionMessageRange lastSystemMessageTimestamp.

#### Implementation of

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md).[`lastSystemMessageTimestamp`](../interfaces/ISyncActionMessageRange.md#lastsystemmessagetimestamp)

***

### messages

> **messages**: [`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)[]

Defined in: [WAProto/index.d.ts:33928](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33928)

SyncActionMessageRange messages.

#### Implementation of

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md).[`messages`](../interfaces/ISyncActionMessageRange.md#messages)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33998](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33998)

Converts this SyncActionMessageRange to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:33935](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33935)

Creates a new SyncActionMessageRange instance using the specified properties.

#### Parameters

##### properties?

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Properties to set

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

SyncActionMessageRange instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:33961](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33961)

Decodes a SyncActionMessageRange message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

SyncActionMessageRange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:33970](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33970)

Decodes a SyncActionMessageRange message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

SyncActionMessageRange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33943](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33943)

Encodes the specified SyncActionMessageRange message. Does not implicitly [verify](SyncActionMessageRange.md#verify) messages.

#### Parameters

##### message

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

SyncActionMessageRange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33951](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33951)

Encodes the specified SyncActionMessageRange message, length delimited. Does not implicitly [verify](SyncActionMessageRange.md#verify) messages.

#### Parameters

##### message

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

SyncActionMessageRange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:33984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33984)

Creates a SyncActionMessageRange message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

SyncActionMessageRange

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33992](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33992)

Creates a plain object from a SyncActionMessageRange message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncActionMessageRange`](SyncActionMessageRange.md)

SyncActionMessageRange

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33977](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33977)

Verifies a SyncActionMessageRange message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
