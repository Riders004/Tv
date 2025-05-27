# Class: PendingKeyExchange

Defined in: [WAProto/index.d.ts:28726](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28726)

Represents a PendingKeyExchange.

## Implements

- [`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

## Constructors

### new PendingKeyExchange()

> **new PendingKeyExchange**(`properties`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:28732](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28732)

Constructs a new PendingKeyExchange.

#### Parameters

##### properties?

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

Properties to set

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

## Properties

### localBaseKey

> **localBaseKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28738](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28738)

PendingKeyExchange localBaseKey.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localBaseKey`](../interfaces/IPendingKeyExchange.md#localbasekey)

***

### localBaseKeyPrivate

> **localBaseKeyPrivate**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28741](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28741)

PendingKeyExchange localBaseKeyPrivate.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localBaseKeyPrivate`](../interfaces/IPendingKeyExchange.md#localbasekeyprivate)

***

### localIdentityKey

> **localIdentityKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28750](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28750)

PendingKeyExchange localIdentityKey.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localIdentityKey`](../interfaces/IPendingKeyExchange.md#localidentitykey)

***

### localIdentityKeyPrivate

> **localIdentityKeyPrivate**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28753](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28753)

PendingKeyExchange localIdentityKeyPrivate.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localIdentityKeyPrivate`](../interfaces/IPendingKeyExchange.md#localidentitykeyprivate)

***

### localRatchetKey

> **localRatchetKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28744](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28744)

PendingKeyExchange localRatchetKey.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localRatchetKey`](../interfaces/IPendingKeyExchange.md#localratchetkey)

***

### localRatchetKeyPrivate

> **localRatchetKeyPrivate**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28747](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28747)

PendingKeyExchange localRatchetKeyPrivate.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localRatchetKeyPrivate`](../interfaces/IPendingKeyExchange.md#localratchetkeyprivate)

***

### sequence

> **sequence**: `number`

Defined in: [WAProto/index.d.ts:28735](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28735)

PendingKeyExchange sequence.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`sequence`](../interfaces/IPendingKeyExchange.md#sequence)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28823](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28823)

Converts this PendingKeyExchange to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:28760](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28760)

Creates a new PendingKeyExchange instance using the specified properties.

#### Parameters

##### properties?

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

Properties to set

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:28786](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28786)

Decodes a PendingKeyExchange message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:28795](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28795)

Decodes a PendingKeyExchange message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28768](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28768)

Encodes the specified PendingKeyExchange message. Does not implicitly [verify](PendingKeyExchange.md#verify) messages.

#### Parameters

##### message

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

PendingKeyExchange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28776](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28776)

Encodes the specified PendingKeyExchange message, length delimited. Does not implicitly [verify](PendingKeyExchange.md#verify) messages.

#### Parameters

##### message

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

PendingKeyExchange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:28809](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28809)

Creates a PendingKeyExchange message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28817](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28817)

Creates a plain object from a PendingKeyExchange message. Also converts values to other types if specified.

#### Parameters

##### message

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28802](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28802)

Verifies a PendingKeyExchange message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
