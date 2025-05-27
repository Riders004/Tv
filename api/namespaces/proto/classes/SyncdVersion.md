# Class: SyncdVersion

Defined in: [WAProto/index.d.ts:35003](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35003)

Represents a SyncdVersion.

## Implements

- [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

## Constructors

### new SyncdVersion()

> **new SyncdVersion**(`properties`?): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:35009](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35009)

Constructs a new SyncdVersion.

#### Parameters

##### properties?

[`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Properties to set

#### Returns

[`SyncdVersion`](SyncdVersion.md)

## Properties

### version

> **version**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:35012](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35012)

SyncdVersion version.

#### Implementation of

[`ISyncdVersion`](../interfaces/ISyncdVersion.md).[`version`](../interfaces/ISyncdVersion.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35082](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35082)

Converts this SyncdVersion to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:35019](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35019)

Creates a new SyncdVersion instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Properties to set

#### Returns

[`SyncdVersion`](SyncdVersion.md)

SyncdVersion instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:35045](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35045)

Decodes a SyncdVersion message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdVersion`](SyncdVersion.md)

SyncdVersion

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:35054](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35054)

Decodes a SyncdVersion message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdVersion`](SyncdVersion.md)

SyncdVersion

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35027](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35027)

Encodes the specified SyncdVersion message. Does not implicitly [verify](SyncdVersion.md#verify) messages.

#### Parameters

##### message

[`ISyncdVersion`](../interfaces/ISyncdVersion.md)

SyncdVersion message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35035](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35035)

Encodes the specified SyncdVersion message, length delimited. Does not implicitly [verify](SyncdVersion.md#verify) messages.

#### Parameters

##### message

[`ISyncdVersion`](../interfaces/ISyncdVersion.md)

SyncdVersion message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:35068](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35068)

Creates a SyncdVersion message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdVersion`](SyncdVersion.md)

SyncdVersion

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35076](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35076)

Creates a plain object from a SyncdVersion message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdVersion`](SyncdVersion.md)

SyncdVersion

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35061](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35061)

Verifies a SyncdVersion message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
