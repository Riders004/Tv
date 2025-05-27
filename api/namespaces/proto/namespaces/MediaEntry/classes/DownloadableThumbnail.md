# Class: DownloadableThumbnail

Defined in: [WAProto/index.d.ts:9192](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9192)

Represents a DownloadableThumbnail.

## Implements

- [`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md)

## Constructors

### new DownloadableThumbnail()

> **new DownloadableThumbnail**(`properties`?): [`DownloadableThumbnail`](DownloadableThumbnail.md)

Defined in: [WAProto/index.d.ts:9198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9198)

Constructs a new DownloadableThumbnail.

#### Parameters

##### properties?

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md)

Properties to set

#### Returns

[`DownloadableThumbnail`](DownloadableThumbnail.md)

## Properties

### directPath

> **directPath**: `string`

Defined in: [WAProto/index.d.ts:9207](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9207)

DownloadableThumbnail directPath.

#### Implementation of

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md).[`directPath`](../interfaces/IDownloadableThumbnail.md#directpath)

***

### fileEncSha256

> **fileEncSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:9204](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9204)

DownloadableThumbnail fileEncSha256.

#### Implementation of

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md).[`fileEncSha256`](../interfaces/IDownloadableThumbnail.md#fileencsha256)

***

### fileSha256

> **fileSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:9201](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9201)

DownloadableThumbnail fileSha256.

#### Implementation of

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md).[`fileSha256`](../interfaces/IDownloadableThumbnail.md#filesha256)

***

### mediaKey

> **mediaKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:9210](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9210)

DownloadableThumbnail mediaKey.

#### Implementation of

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md).[`mediaKey`](../interfaces/IDownloadableThumbnail.md#mediakey)

***

### mediaKeyTimestamp

> **mediaKeyTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:9213](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9213)

DownloadableThumbnail mediaKeyTimestamp.

#### Implementation of

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md).[`mediaKeyTimestamp`](../interfaces/IDownloadableThumbnail.md#mediakeytimestamp)

***

### objectId

> **objectId**: `string`

Defined in: [WAProto/index.d.ts:9216](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9216)

DownloadableThumbnail objectId.

#### Implementation of

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md).[`objectId`](../interfaces/IDownloadableThumbnail.md#objectid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9286](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9286)

Converts this DownloadableThumbnail to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DownloadableThumbnail`](DownloadableThumbnail.md)

Defined in: [WAProto/index.d.ts:9223](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9223)

Creates a new DownloadableThumbnail instance using the specified properties.

#### Parameters

##### properties?

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md)

Properties to set

#### Returns

[`DownloadableThumbnail`](DownloadableThumbnail.md)

DownloadableThumbnail instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DownloadableThumbnail`](DownloadableThumbnail.md)

Defined in: [WAProto/index.d.ts:9249](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9249)

Decodes a DownloadableThumbnail message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DownloadableThumbnail`](DownloadableThumbnail.md)

DownloadableThumbnail

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DownloadableThumbnail`](DownloadableThumbnail.md)

Defined in: [WAProto/index.d.ts:9258](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9258)

Decodes a DownloadableThumbnail message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DownloadableThumbnail`](DownloadableThumbnail.md)

DownloadableThumbnail

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9231](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9231)

Encodes the specified DownloadableThumbnail message. Does not implicitly [verify](DownloadableThumbnail.md#verify) messages.

#### Parameters

##### message

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md)

DownloadableThumbnail message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9239](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9239)

Encodes the specified DownloadableThumbnail message, length delimited. Does not implicitly [verify](DownloadableThumbnail.md#verify) messages.

#### Parameters

##### message

[`IDownloadableThumbnail`](../interfaces/IDownloadableThumbnail.md)

DownloadableThumbnail message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DownloadableThumbnail`](DownloadableThumbnail.md)

Defined in: [WAProto/index.d.ts:9272](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9272)

Creates a DownloadableThumbnail message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DownloadableThumbnail`](DownloadableThumbnail.md)

DownloadableThumbnail

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:9280](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9280)

Creates a plain object from a DownloadableThumbnail message. Also converts values to other types if specified.

#### Parameters

##### message

[`DownloadableThumbnail`](DownloadableThumbnail.md)

DownloadableThumbnail

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:9265](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9265)

Verifies a DownloadableThumbnail message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
