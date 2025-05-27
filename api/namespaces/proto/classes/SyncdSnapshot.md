# Class: SyncdSnapshot

Defined in: [WAProto/index.d.ts:34814](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34814)

Represents a SyncdSnapshot.

## Implements

- [`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

## Constructors

### new SyncdSnapshot()

> **new SyncdSnapshot**(`properties`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:34820](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34820)

Constructs a new SyncdSnapshot.

#### Parameters

##### properties?

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

Properties to set

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

## Properties

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:34832](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34832)

SyncdSnapshot keyId.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`keyId`](../interfaces/ISyncdSnapshot.md#keyid)

***

### mac

> **mac**: `Uint8Array`

Defined in: [WAProto/index.d.ts:34829](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34829)

SyncdSnapshot mac.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`mac`](../interfaces/ISyncdSnapshot.md#mac)

***

### records

> **records**: [`ISyncdRecord`](../interfaces/ISyncdRecord.md)[]

Defined in: [WAProto/index.d.ts:34826](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34826)

SyncdSnapshot records.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`records`](../interfaces/ISyncdSnapshot.md#records)

***

### version?

> `optional` **version**: `null` \| [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Defined in: [WAProto/index.d.ts:34823](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34823)

SyncdSnapshot version.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`version`](../interfaces/ISyncdSnapshot.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34902](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34902)

Converts this SyncdSnapshot to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:34839](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34839)

Creates a new SyncdSnapshot instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

Properties to set

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:34865](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34865)

Decodes a SyncdSnapshot message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:34874](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34874)

Decodes a SyncdSnapshot message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34847](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34847)

Encodes the specified SyncdSnapshot message. Does not implicitly [verify](SyncdSnapshot.md#verify) messages.

#### Parameters

##### message

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

SyncdSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34855](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34855)

Encodes the specified SyncdSnapshot message, length delimited. Does not implicitly [verify](SyncdSnapshot.md#verify) messages.

#### Parameters

##### message

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

SyncdSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:34888](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34888)

Creates a SyncdSnapshot message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34896](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34896)

Creates a plain object from a SyncdSnapshot message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34881](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34881)

Verifies a SyncdSnapshot message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
