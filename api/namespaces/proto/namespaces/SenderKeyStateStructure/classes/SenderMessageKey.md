# Class: SenderMessageKey

Defined in: [WAProto/index.d.ts:27949](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27949)

Represents a SenderMessageKey.

## Implements

- [`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

## Constructors

### new SenderMessageKey()

> **new SenderMessageKey**(`properties`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:27955](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27955)

Constructs a new SenderMessageKey.

#### Parameters

##### properties?

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

Properties to set

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

## Properties

### iteration

> **iteration**: `number`

Defined in: [WAProto/index.d.ts:27958](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27958)

SenderMessageKey iteration.

#### Implementation of

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md).[`iteration`](../interfaces/ISenderMessageKey.md#iteration)

***

### seed

> **seed**: `Uint8Array`

Defined in: [WAProto/index.d.ts:27961](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27961)

SenderMessageKey seed.

#### Implementation of

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md).[`seed`](../interfaces/ISenderMessageKey.md#seed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28031](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28031)

Converts this SenderMessageKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:27968](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27968)

Creates a new SenderMessageKey instance using the specified properties.

#### Parameters

##### properties?

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

Properties to set

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:27994](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27994)

Decodes a SenderMessageKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:28003](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28003)

Decodes a SenderMessageKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27976](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27976)

Encodes the specified SenderMessageKey message. Does not implicitly [verify](SenderMessageKey.md#verify) messages.

#### Parameters

##### message

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

SenderMessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27984)

Encodes the specified SenderMessageKey message, length delimited. Does not implicitly [verify](SenderMessageKey.md#verify) messages.

#### Parameters

##### message

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

SenderMessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:28017](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28017)

Creates a SenderMessageKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28025)

Creates a plain object from a SenderMessageKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28010](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28010)

Verifies a SenderMessageKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
