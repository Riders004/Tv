# Class: PendingPreKey

Defined in: [WAProto/index.d.ts:28840](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28840)

Represents a PendingPreKey.

## Implements

- [`IPendingPreKey`](../interfaces/IPendingPreKey.md)

## Constructors

### new PendingPreKey()

> **new PendingPreKey**(`properties`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:28846](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28846)

Constructs a new PendingPreKey.

#### Parameters

##### properties?

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

Properties to set

#### Returns

[`PendingPreKey`](PendingPreKey.md)

## Properties

### baseKey

> **baseKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28855](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28855)

PendingPreKey baseKey.

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`baseKey`](../interfaces/IPendingPreKey.md#basekey)

***

### preKeyId

> **preKeyId**: `number`

Defined in: [WAProto/index.d.ts:28849](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28849)

PendingPreKey preKeyId.

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`preKeyId`](../interfaces/IPendingPreKey.md#prekeyid)

***

### signedPreKeyId

> **signedPreKeyId**: `number`

Defined in: [WAProto/index.d.ts:28852](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28852)

PendingPreKey signedPreKeyId.

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`signedPreKeyId`](../interfaces/IPendingPreKey.md#signedprekeyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28925](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28925)

Converts this PendingPreKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:28862](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28862)

Creates a new PendingPreKey instance using the specified properties.

#### Parameters

##### properties?

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

Properties to set

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:28888](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28888)

Decodes a PendingPreKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:28897](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28897)

Decodes a PendingPreKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28870)

Encodes the specified PendingPreKey message. Does not implicitly [verify](PendingPreKey.md#verify) messages.

#### Parameters

##### message

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

PendingPreKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28878](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28878)

Encodes the specified PendingPreKey message, length delimited. Does not implicitly [verify](PendingPreKey.md#verify) messages.

#### Parameters

##### message

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

PendingPreKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:28911](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28911)

Creates a PendingPreKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28919)

Creates a plain object from a PendingPreKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28904](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28904)

Verifies a PendingPreKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
