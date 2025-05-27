# Class: SenderSigningKey

Defined in: [WAProto/index.d.ts:28045](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28045)

Represents a SenderSigningKey.

## Implements

- [`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

## Constructors

### new SenderSigningKey()

> **new SenderSigningKey**(`properties`?): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:28051](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28051)

Constructs a new SenderSigningKey.

#### Parameters

##### properties?

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

Properties to set

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

## Properties

### private

> **private**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28057](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28057)

SenderSigningKey private.

#### Implementation of

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md).[`private`](../interfaces/ISenderSigningKey.md#private)

***

### public

> **public**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28054](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28054)

SenderSigningKey public.

#### Implementation of

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md).[`public`](../interfaces/ISenderSigningKey.md#public)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28127](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28127)

Converts this SenderSigningKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:28064](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28064)

Creates a new SenderSigningKey instance using the specified properties.

#### Parameters

##### properties?

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

Properties to set

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

SenderSigningKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:28090](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28090)

Decodes a SenderSigningKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

SenderSigningKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:28099](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28099)

Decodes a SenderSigningKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

SenderSigningKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28072](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28072)

Encodes the specified SenderSigningKey message. Does not implicitly [verify](SenderSigningKey.md#verify) messages.

#### Parameters

##### message

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

SenderSigningKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28080](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28080)

Encodes the specified SenderSigningKey message, length delimited. Does not implicitly [verify](SenderSigningKey.md#verify) messages.

#### Parameters

##### message

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

SenderSigningKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:28113](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28113)

Creates a SenderSigningKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

SenderSigningKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28121](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28121)

Creates a plain object from a SenderSigningKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderSigningKey`](SenderSigningKey.md)

SenderSigningKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28106](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28106)

Verifies a SenderSigningKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
