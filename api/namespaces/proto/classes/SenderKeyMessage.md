# Class: SenderKeyMessage

Defined in: [WAProto/index.d.ts:27554](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27554)

Represents a SenderKeyMessage.

## Implements

- [`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

## Constructors

### new SenderKeyMessage()

> **new SenderKeyMessage**(`properties`?): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:27560](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27560)

Constructs a new SenderKeyMessage.

#### Parameters

##### properties?

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

Properties to set

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

## Properties

### ciphertext

> **ciphertext**: `Uint8Array`

Defined in: [WAProto/index.d.ts:27569](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27569)

SenderKeyMessage ciphertext.

#### Implementation of

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md).[`ciphertext`](../interfaces/ISenderKeyMessage.md#ciphertext)

***

### id

> **id**: `number`

Defined in: [WAProto/index.d.ts:27563](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27563)

SenderKeyMessage id.

#### Implementation of

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md).[`id`](../interfaces/ISenderKeyMessage.md#id)

***

### iteration

> **iteration**: `number`

Defined in: [WAProto/index.d.ts:27566](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27566)

SenderKeyMessage iteration.

#### Implementation of

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md).[`iteration`](../interfaces/ISenderKeyMessage.md#iteration)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27639](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27639)

Converts this SenderKeyMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:27576](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27576)

Creates a new SenderKeyMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

Properties to set

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

SenderKeyMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:27602](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27602)

Decodes a SenderKeyMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

SenderKeyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:27611](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27611)

Decodes a SenderKeyMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

SenderKeyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27584](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27584)

Encodes the specified SenderKeyMessage message. Does not implicitly [verify](SenderKeyMessage.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

SenderKeyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27592](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27592)

Encodes the specified SenderKeyMessage message, length delimited. Does not implicitly [verify](SenderKeyMessage.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

SenderKeyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:27625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27625)

Creates a SenderKeyMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

SenderKeyMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27633](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27633)

Creates a plain object from a SenderKeyMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderKeyMessage`](SenderKeyMessage.md)

SenderKeyMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27618](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27618)

Verifies a SenderKeyMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
