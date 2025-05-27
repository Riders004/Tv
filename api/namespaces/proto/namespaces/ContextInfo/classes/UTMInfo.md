# Class: UTMInfo

Defined in: [WAProto/index.d.ts:5038](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5038)

Represents a UTMInfo.

## Implements

- [`IUTMInfo`](../interfaces/IUTMInfo.md)

## Constructors

### new UTMInfo()

> **new UTMInfo**(`properties`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:5044](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5044)

Constructs a new UTMInfo.

#### Parameters

##### properties?

[`IUTMInfo`](../interfaces/IUTMInfo.md)

Properties to set

#### Returns

[`UTMInfo`](UTMInfo.md)

## Properties

### utmCampaign

> **utmCampaign**: `string`

Defined in: [WAProto/index.d.ts:5050](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5050)

UTMInfo utmCampaign.

#### Implementation of

[`IUTMInfo`](../interfaces/IUTMInfo.md).[`utmCampaign`](../interfaces/IUTMInfo.md#utmcampaign)

***

### utmSource

> **utmSource**: `string`

Defined in: [WAProto/index.d.ts:5047](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5047)

UTMInfo utmSource.

#### Implementation of

[`IUTMInfo`](../interfaces/IUTMInfo.md).[`utmSource`](../interfaces/IUTMInfo.md#utmsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5120](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5120)

Converts this UTMInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:5057](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5057)

Creates a new UTMInfo instance using the specified properties.

#### Parameters

##### properties?

[`IUTMInfo`](../interfaces/IUTMInfo.md)

Properties to set

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:5083](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5083)

Decodes a UTMInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:5092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5092)

Decodes a UTMInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5065](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5065)

Encodes the specified UTMInfo message. Does not implicitly [verify](UTMInfo.md#verify) messages.

#### Parameters

##### message

[`IUTMInfo`](../interfaces/IUTMInfo.md)

UTMInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5073](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5073)

Encodes the specified UTMInfo message, length delimited. Does not implicitly [verify](UTMInfo.md#verify) messages.

#### Parameters

##### message

[`IUTMInfo`](../interfaces/IUTMInfo.md)

UTMInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:5106](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5106)

Creates a UTMInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:5114](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5114)

Creates a plain object from a UTMInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`UTMInfo`](UTMInfo.md)

UTMInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5099](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5099)

Verifies a UTMInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
