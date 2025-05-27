# Class: EncReactionMessage

Defined in: [WAProto/index.d.ts:13234](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13234)

Represents an EncReactionMessage.

## Implements

- [`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

## Constructors

### new EncReactionMessage()

> **new EncReactionMessage**(`properties`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:13240](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13240)

Constructs a new EncReactionMessage.

#### Parameters

##### properties?

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

Properties to set

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

## Properties

### encIv

> **encIv**: `Uint8Array`

Defined in: [WAProto/index.d.ts:13249](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13249)

EncReactionMessage encIv.

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`encIv`](../interfaces/IEncReactionMessage.md#enciv)

***

### encPayload

> **encPayload**: `Uint8Array`

Defined in: [WAProto/index.d.ts:13246](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13246)

EncReactionMessage encPayload.

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`encPayload`](../interfaces/IEncReactionMessage.md#encpayload)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:13243](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13243)

EncReactionMessage targetMessageKey.

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`targetMessageKey`](../interfaces/IEncReactionMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13319](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13319)

Converts this EncReactionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:13256](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13256)

Creates a new EncReactionMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

Properties to set

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:13282](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13282)

Decodes an EncReactionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:13291](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13291)

Decodes an EncReactionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13264](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13264)

Encodes the specified EncReactionMessage message. Does not implicitly [verify](EncReactionMessage.md#verify) messages.

#### Parameters

##### message

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

EncReactionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13272](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13272)

Encodes the specified EncReactionMessage message, length delimited. Does not implicitly [verify](EncReactionMessage.md#verify) messages.

#### Parameters

##### message

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

EncReactionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:13305](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13305)

Creates an EncReactionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:13313](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13313)

Creates a plain object from an EncReactionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13298](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13298)

Verifies an EncReactionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
