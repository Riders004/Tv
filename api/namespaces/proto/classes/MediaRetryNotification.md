# Class: MediaRetryNotification

Defined in: [WAProto/index.d.ts:9502](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9502)

Represents a MediaRetryNotification.

## Implements

- [`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

## Constructors

### new MediaRetryNotification()

> **new MediaRetryNotification**(`properties`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:9508](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9508)

Constructs a new MediaRetryNotification.

#### Parameters

##### properties?

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

Properties to set

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

## Properties

### directPath

> **directPath**: `string`

Defined in: [WAProto/index.d.ts:9514](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9514)

MediaRetryNotification directPath.

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`directPath`](../interfaces/IMediaRetryNotification.md#directpath)

***

### result

> **result**: [`ResultType`](../namespaces/MediaRetryNotification/enumerations/ResultType.md)

Defined in: [WAProto/index.d.ts:9517](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9517)

MediaRetryNotification result.

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`result`](../interfaces/IMediaRetryNotification.md#result)

***

### stanzaId

> **stanzaId**: `string`

Defined in: [WAProto/index.d.ts:9511](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9511)

MediaRetryNotification stanzaId.

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`stanzaId`](../interfaces/IMediaRetryNotification.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9587](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9587)

Converts this MediaRetryNotification to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:9524](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9524)

Creates a new MediaRetryNotification instance using the specified properties.

#### Parameters

##### properties?

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

Properties to set

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:9550](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9550)

Decodes a MediaRetryNotification message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:9559](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9559)

Decodes a MediaRetryNotification message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9532](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9532)

Encodes the specified MediaRetryNotification message. Does not implicitly [verify](MediaRetryNotification.md#verify) messages.

#### Parameters

##### message

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

MediaRetryNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9540](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9540)

Encodes the specified MediaRetryNotification message, length delimited. Does not implicitly [verify](MediaRetryNotification.md#verify) messages.

#### Parameters

##### message

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

MediaRetryNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:9573](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9573)

Creates a MediaRetryNotification message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:9581](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9581)

Creates a plain object from a MediaRetryNotification message. Also converts values to other types if specified.

#### Parameters

##### message

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:9566](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9566)

Verifies a MediaRetryNotification message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
