# Class: SyncdMutation

Defined in: [WAProto/index.d.ts:34373](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34373)

Represents a SyncdMutation.

## Implements

- [`ISyncdMutation`](../interfaces/ISyncdMutation.md)

## Constructors

### new SyncdMutation()

> **new SyncdMutation**(`properties`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:34379](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34379)

Constructs a new SyncdMutation.

#### Parameters

##### properties?

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

Properties to set

#### Returns

[`SyncdMutation`](SyncdMutation.md)

## Properties

### operation

> **operation**: [`SyncdOperation`](../namespaces/SyncdMutation/enumerations/SyncdOperation.md)

Defined in: [WAProto/index.d.ts:34382](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34382)

SyncdMutation operation.

#### Implementation of

[`ISyncdMutation`](../interfaces/ISyncdMutation.md).[`operation`](../interfaces/ISyncdMutation.md#operation)

***

### record?

> `optional` **record**: `null` \| [`ISyncdRecord`](../interfaces/ISyncdRecord.md)

Defined in: [WAProto/index.d.ts:34385](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34385)

SyncdMutation record.

#### Implementation of

[`ISyncdMutation`](../interfaces/ISyncdMutation.md).[`record`](../interfaces/ISyncdMutation.md#record)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34455)

Converts this SyncdMutation to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:34392](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34392)

Creates a new SyncdMutation instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

Properties to set

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:34418](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34418)

Decodes a SyncdMutation message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:34427](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34427)

Decodes a SyncdMutation message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34400](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34400)

Encodes the specified SyncdMutation message. Does not implicitly [verify](SyncdMutation.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

SyncdMutation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34408](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34408)

Encodes the specified SyncdMutation message, length delimited. Does not implicitly [verify](SyncdMutation.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

SyncdMutation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:34441](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34441)

Creates a SyncdMutation message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34449](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34449)

Creates a plain object from a SyncdMutation message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34434](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34434)

Verifies a SyncdMutation message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
