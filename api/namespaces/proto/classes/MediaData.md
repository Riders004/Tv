# Class: MediaData

Defined in: [WAProto/index.d.ts:8911](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8911)

Represents a MediaData.

## Implements

- [`IMediaData`](../interfaces/IMediaData.md)

## Constructors

### new MediaData()

> **new MediaData**(`properties`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:8917](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8917)

Constructs a new MediaData.

#### Parameters

##### properties?

[`IMediaData`](../interfaces/IMediaData.md)

Properties to set

#### Returns

[`MediaData`](MediaData.md)

## Properties

### localPath

> **localPath**: `string`

Defined in: [WAProto/index.d.ts:8920](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8920)

MediaData localPath.

#### Implementation of

[`IMediaData`](../interfaces/IMediaData.md).[`localPath`](../interfaces/IMediaData.md#localpath)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8990](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8990)

Converts this MediaData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:8927](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8927)

Creates a new MediaData instance using the specified properties.

#### Parameters

##### properties?

[`IMediaData`](../interfaces/IMediaData.md)

Properties to set

#### Returns

[`MediaData`](MediaData.md)

MediaData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:8953](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8953)

Decodes a MediaData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MediaData`](MediaData.md)

MediaData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:8962](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8962)

Decodes a MediaData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MediaData`](MediaData.md)

MediaData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8935](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8935)

Encodes the specified MediaData message. Does not implicitly [verify](MediaData.md#verify) messages.

#### Parameters

##### message

[`IMediaData`](../interfaces/IMediaData.md)

MediaData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8943](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8943)

Encodes the specified MediaData message, length delimited. Does not implicitly [verify](MediaData.md#verify) messages.

#### Parameters

##### message

[`IMediaData`](../interfaces/IMediaData.md)

MediaData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:8976](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8976)

Creates a MediaData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MediaData`](MediaData.md)

MediaData

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8984)

Creates a plain object from a MediaData message. Also converts values to other types if specified.

#### Parameters

##### message

[`MediaData`](MediaData.md)

MediaData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8969](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8969)

Verifies a MediaData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
