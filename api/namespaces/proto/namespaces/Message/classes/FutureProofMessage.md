# Class: FutureProofMessage

Defined in: [WAProto/index.d.ts:14109](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14109)

Represents a FutureProofMessage.

## Implements

- [`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

## Constructors

### new FutureProofMessage()

> **new FutureProofMessage**(`properties`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:14115](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14115)

Constructs a new FutureProofMessage.

#### Parameters

##### properties?

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

Properties to set

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:14118](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14118)

FutureProofMessage message.

#### Implementation of

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md).[`message`](../interfaces/IFutureProofMessage.md#message)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14188](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14188)

Converts this FutureProofMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:14125](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14125)

Creates a new FutureProofMessage instance using the specified properties.

#### Parameters

##### properties?

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

Properties to set

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:14151](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14151)

Decodes a FutureProofMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:14160](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14160)

Decodes a FutureProofMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14133](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14133)

Encodes the specified FutureProofMessage message. Does not implicitly [verify](FutureProofMessage.md#verify) messages.

#### Parameters

##### message

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

FutureProofMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14141)

Encodes the specified FutureProofMessage message, length delimited. Does not implicitly [verify](FutureProofMessage.md#verify) messages.

#### Parameters

##### message

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

FutureProofMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:14174](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14174)

Creates a FutureProofMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14182](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14182)

Creates a plain object from a FutureProofMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`FutureProofMessage`](FutureProofMessage.md)

FutureProofMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14167](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14167)

Verifies a FutureProofMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
