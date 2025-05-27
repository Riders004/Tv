# Class: PremiumMessageInfo

Defined in: [WAProto/index.d.ts:26445](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26445)

Represents a PremiumMessageInfo.

## Implements

- [`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

## Constructors

### new PremiumMessageInfo()

> **new PremiumMessageInfo**(`properties`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:26451](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26451)

Constructs a new PremiumMessageInfo.

#### Parameters

##### properties?

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

Properties to set

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

## Properties

### serverCampaignId

> **serverCampaignId**: `string`

Defined in: [WAProto/index.d.ts:26454](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26454)

PremiumMessageInfo serverCampaignId.

#### Implementation of

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md).[`serverCampaignId`](../interfaces/IPremiumMessageInfo.md#servercampaignid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26524](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26524)

Converts this PremiumMessageInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:26461](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26461)

Creates a new PremiumMessageInfo instance using the specified properties.

#### Parameters

##### properties?

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

Properties to set

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:26487](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26487)

Decodes a PremiumMessageInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:26496](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26496)

Decodes a PremiumMessageInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26469](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26469)

Encodes the specified PremiumMessageInfo message. Does not implicitly [verify](PremiumMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

PremiumMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26477](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26477)

Encodes the specified PremiumMessageInfo message, length delimited. Does not implicitly [verify](PremiumMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

PremiumMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:26510](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26510)

Creates a PremiumMessageInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:26518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26518)

Creates a plain object from a PremiumMessageInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26503](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26503)

Verifies a PremiumMessageInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
