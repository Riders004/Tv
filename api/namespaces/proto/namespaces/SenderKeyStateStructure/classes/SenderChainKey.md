# Class: SenderChainKey

Defined in: [WAProto/index.d.ts:27853](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27853)

Represents a SenderChainKey.

## Implements

- [`ISenderChainKey`](../interfaces/ISenderChainKey.md)

## Constructors

### new SenderChainKey()

> **new SenderChainKey**(`properties`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:27859](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27859)

Constructs a new SenderChainKey.

#### Parameters

##### properties?

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

Properties to set

#### Returns

[`SenderChainKey`](SenderChainKey.md)

## Properties

### iteration

> **iteration**: `number`

Defined in: [WAProto/index.d.ts:27862](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27862)

SenderChainKey iteration.

#### Implementation of

[`ISenderChainKey`](../interfaces/ISenderChainKey.md).[`iteration`](../interfaces/ISenderChainKey.md#iteration)

***

### seed

> **seed**: `Uint8Array`

Defined in: [WAProto/index.d.ts:27865](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27865)

SenderChainKey seed.

#### Implementation of

[`ISenderChainKey`](../interfaces/ISenderChainKey.md).[`seed`](../interfaces/ISenderChainKey.md#seed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27935](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27935)

Converts this SenderChainKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:27872](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27872)

Creates a new SenderChainKey instance using the specified properties.

#### Parameters

##### properties?

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

Properties to set

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:27898](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27898)

Decodes a SenderChainKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:27907](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27907)

Decodes a SenderChainKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27880](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27880)

Encodes the specified SenderChainKey message. Does not implicitly [verify](SenderChainKey.md#verify) messages.

#### Parameters

##### message

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

SenderChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27888](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27888)

Encodes the specified SenderChainKey message, length delimited. Does not implicitly [verify](SenderChainKey.md#verify) messages.

#### Parameters

##### message

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

SenderChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:27921](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27921)

Creates a SenderChainKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27929](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27929)

Creates a plain object from a SenderChainKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27914](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27914)

Verifies a SenderChainKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
