# Class: ExternalBlobReference

Defined in: [WAProto/index.d.ts:6557](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6557)

Represents an ExternalBlobReference.

## Implements

- [`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

## Constructors

### new ExternalBlobReference()

> **new ExternalBlobReference**(`properties`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:6563](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6563)

Constructs a new ExternalBlobReference.

#### Parameters

##### properties?

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

Properties to set

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

## Properties

### directPath

> **directPath**: `string`

Defined in: [WAProto/index.d.ts:6569](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6569)

ExternalBlobReference directPath.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`directPath`](../interfaces/IExternalBlobReference.md#directpath)

***

### fileEncSha256

> **fileEncSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:6581](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6581)

ExternalBlobReference fileEncSha256.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileEncSha256`](../interfaces/IExternalBlobReference.md#fileencsha256)

***

### fileSha256

> **fileSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:6578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6578)

ExternalBlobReference fileSha256.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileSha256`](../interfaces/IExternalBlobReference.md#filesha256)

***

### fileSizeBytes

> **fileSizeBytes**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:6575](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6575)

ExternalBlobReference fileSizeBytes.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileSizeBytes`](../interfaces/IExternalBlobReference.md#filesizebytes)

***

### handle

> **handle**: `string`

Defined in: [WAProto/index.d.ts:6572](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6572)

ExternalBlobReference handle.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`handle`](../interfaces/IExternalBlobReference.md#handle)

***

### mediaKey

> **mediaKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:6566](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6566)

ExternalBlobReference mediaKey.

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`mediaKey`](../interfaces/IExternalBlobReference.md#mediakey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6651](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6651)

Converts this ExternalBlobReference to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:6588](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6588)

Creates a new ExternalBlobReference instance using the specified properties.

#### Parameters

##### properties?

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

Properties to set

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:6614](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6614)

Decodes an ExternalBlobReference message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:6623](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6623)

Decodes an ExternalBlobReference message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6596](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6596)

Encodes the specified ExternalBlobReference message. Does not implicitly [verify](ExternalBlobReference.md#verify) messages.

#### Parameters

##### message

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

ExternalBlobReference message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6604)

Encodes the specified ExternalBlobReference message, length delimited. Does not implicitly [verify](ExternalBlobReference.md#verify) messages.

#### Parameters

##### message

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

ExternalBlobReference message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:6637](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6637)

Creates an ExternalBlobReference message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:6645](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6645)

Creates a plain object from an ExternalBlobReference message. Also converts values to other types if specified.

#### Parameters

##### message

[`ExternalBlobReference`](ExternalBlobReference.md)

ExternalBlobReference

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6630](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6630)

Verifies an ExternalBlobReference message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
