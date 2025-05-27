# Class: ProgressiveJpegDetails

Defined in: [WAProto/index.d.ts:9300](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9300)

Represents a ProgressiveJpegDetails.

## Implements

- [`IProgressiveJpegDetails`](../interfaces/IProgressiveJpegDetails.md)

## Constructors

### new ProgressiveJpegDetails()

> **new ProgressiveJpegDetails**(`properties`?): [`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

Defined in: [WAProto/index.d.ts:9306](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9306)

Constructs a new ProgressiveJpegDetails.

#### Parameters

##### properties?

[`IProgressiveJpegDetails`](../interfaces/IProgressiveJpegDetails.md)

Properties to set

#### Returns

[`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

## Properties

### scanLengths

> **scanLengths**: (`number` \| `Long`)[]

Defined in: [WAProto/index.d.ts:9309](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9309)

ProgressiveJpegDetails scanLengths.

#### Implementation of

[`IProgressiveJpegDetails`](../interfaces/IProgressiveJpegDetails.md).[`scanLengths`](../interfaces/IProgressiveJpegDetails.md#scanlengths)

***

### sidecar

> **sidecar**: `Uint8Array`

Defined in: [WAProto/index.d.ts:9312](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9312)

ProgressiveJpegDetails sidecar.

#### Implementation of

[`IProgressiveJpegDetails`](../interfaces/IProgressiveJpegDetails.md).[`sidecar`](../interfaces/IProgressiveJpegDetails.md#sidecar)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9382](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9382)

Converts this ProgressiveJpegDetails to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

Defined in: [WAProto/index.d.ts:9319](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9319)

Creates a new ProgressiveJpegDetails instance using the specified properties.

#### Parameters

##### properties?

[`IProgressiveJpegDetails`](../interfaces/IProgressiveJpegDetails.md)

Properties to set

#### Returns

[`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

ProgressiveJpegDetails instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

Defined in: [WAProto/index.d.ts:9345](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9345)

Decodes a ProgressiveJpegDetails message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

ProgressiveJpegDetails

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

Defined in: [WAProto/index.d.ts:9354](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9354)

Decodes a ProgressiveJpegDetails message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

ProgressiveJpegDetails

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9327](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9327)

Encodes the specified ProgressiveJpegDetails message. Does not implicitly [verify](ProgressiveJpegDetails.md#verify) messages.

#### Parameters

##### message

[`IProgressiveJpegDetails`](../interfaces/IProgressiveJpegDetails.md)

ProgressiveJpegDetails message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9335](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9335)

Encodes the specified ProgressiveJpegDetails message, length delimited. Does not implicitly [verify](ProgressiveJpegDetails.md#verify) messages.

#### Parameters

##### message

[`IProgressiveJpegDetails`](../interfaces/IProgressiveJpegDetails.md)

ProgressiveJpegDetails message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

Defined in: [WAProto/index.d.ts:9368](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9368)

Creates a ProgressiveJpegDetails message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

ProgressiveJpegDetails

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:9376](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9376)

Creates a plain object from a ProgressiveJpegDetails message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProgressiveJpegDetails`](ProgressiveJpegDetails.md)

ProgressiveJpegDetails

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:9361](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9361)

Verifies a ProgressiveJpegDetails message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
