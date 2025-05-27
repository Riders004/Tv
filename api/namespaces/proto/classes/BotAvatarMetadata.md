# Class: BotAvatarMetadata

Defined in: [WAProto/index.d.ts:1249](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1249)

Represents a BotAvatarMetadata.

## Implements

- [`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

## Constructors

### new BotAvatarMetadata()

> **new BotAvatarMetadata**(`properties`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:1255](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1255)

Constructs a new BotAvatarMetadata.

#### Parameters

##### properties?

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

Properties to set

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

## Properties

### action

> **action**: `number`

Defined in: [WAProto/index.d.ts:1264](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1264)

BotAvatarMetadata action.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`action`](../interfaces/IBotAvatarMetadata.md#action)

***

### behaviorGraph

> **behaviorGraph**: `string`

Defined in: [WAProto/index.d.ts:1261](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1261)

BotAvatarMetadata behaviorGraph.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`behaviorGraph`](../interfaces/IBotAvatarMetadata.md#behaviorgraph)

***

### intensity

> **intensity**: `number`

Defined in: [WAProto/index.d.ts:1267](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1267)

BotAvatarMetadata intensity.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`intensity`](../interfaces/IBotAvatarMetadata.md#intensity)

***

### sentiment

> **sentiment**: `number`

Defined in: [WAProto/index.d.ts:1258](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1258)

BotAvatarMetadata sentiment.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`sentiment`](../interfaces/IBotAvatarMetadata.md#sentiment)

***

### wordCount

> **wordCount**: `number`

Defined in: [WAProto/index.d.ts:1270](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1270)

BotAvatarMetadata wordCount.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`wordCount`](../interfaces/IBotAvatarMetadata.md#wordcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1340](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1340)

Converts this BotAvatarMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:1277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1277)

Creates a new BotAvatarMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

Properties to set

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:1303](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1303)

Decodes a BotAvatarMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:1312](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1312)

Decodes a BotAvatarMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1285](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1285)

Encodes the specified BotAvatarMetadata message. Does not implicitly [verify](BotAvatarMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

BotAvatarMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1293](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1293)

Encodes the specified BotAvatarMetadata message, length delimited. Does not implicitly [verify](BotAvatarMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

BotAvatarMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:1326](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1326)

Creates a BotAvatarMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:1334](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1334)

Creates a plain object from a BotAvatarMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1319](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1319)

Verifies a BotAvatarMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
