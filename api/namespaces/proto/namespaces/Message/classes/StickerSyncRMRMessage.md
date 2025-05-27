# Class: StickerSyncRMRMessage

Defined in: [WAProto/index.d.ts:22347](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22347)

Represents a StickerSyncRMRMessage.

## Implements

- [`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

## Constructors

### new StickerSyncRMRMessage()

> **new StickerSyncRMRMessage**(`properties`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:22353](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22353)

Constructs a new StickerSyncRMRMessage.

#### Parameters

##### properties?

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

Properties to set

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

## Properties

### filehash

> **filehash**: `string`[]

Defined in: [WAProto/index.d.ts:22356](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22356)

StickerSyncRMRMessage filehash.

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`filehash`](../interfaces/IStickerSyncRMRMessage.md#filehash)

***

### requestTimestamp

> **requestTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:22362](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22362)

StickerSyncRMRMessage requestTimestamp.

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`requestTimestamp`](../interfaces/IStickerSyncRMRMessage.md#requesttimestamp)

***

### rmrSource

> **rmrSource**: `string`

Defined in: [WAProto/index.d.ts:22359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22359)

StickerSyncRMRMessage rmrSource.

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`rmrSource`](../interfaces/IStickerSyncRMRMessage.md#rmrsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22432](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22432)

Converts this StickerSyncRMRMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:22369](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22369)

Creates a new StickerSyncRMRMessage instance using the specified properties.

#### Parameters

##### properties?

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

Properties to set

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:22395](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22395)

Decodes a StickerSyncRMRMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:22404](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22404)

Decodes a StickerSyncRMRMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22377](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22377)

Encodes the specified StickerSyncRMRMessage message. Does not implicitly [verify](StickerSyncRMRMessage.md#verify) messages.

#### Parameters

##### message

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

StickerSyncRMRMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22385](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22385)

Encodes the specified StickerSyncRMRMessage message, length delimited. Does not implicitly [verify](StickerSyncRMRMessage.md#verify) messages.

#### Parameters

##### message

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

StickerSyncRMRMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:22418](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22418)

Creates a StickerSyncRMRMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:22426](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22426)

Creates a plain object from a StickerSyncRMRMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22411](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22411)

Verifies a StickerSyncRMRMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
