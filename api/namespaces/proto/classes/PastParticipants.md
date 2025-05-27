# Class: PastParticipants

Defined in: [WAProto/index.d.ts:24746](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24746)

Represents a PastParticipants.

## Implements

- [`IPastParticipants`](../interfaces/IPastParticipants.md)

## Constructors

### new PastParticipants()

> **new PastParticipants**(`properties`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:24752](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24752)

Constructs a new PastParticipants.

#### Parameters

##### properties?

[`IPastParticipants`](../interfaces/IPastParticipants.md)

Properties to set

#### Returns

[`PastParticipants`](PastParticipants.md)

## Properties

### groupJid

> **groupJid**: `string`

Defined in: [WAProto/index.d.ts:24755](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24755)

PastParticipants groupJid.

#### Implementation of

[`IPastParticipants`](../interfaces/IPastParticipants.md).[`groupJid`](../interfaces/IPastParticipants.md#groupjid)

***

### pastParticipants

> **pastParticipants**: [`IPastParticipant`](../interfaces/IPastParticipant.md)[]

Defined in: [WAProto/index.d.ts:24758](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24758)

PastParticipants pastParticipants.

#### Implementation of

[`IPastParticipants`](../interfaces/IPastParticipants.md).[`pastParticipants`](../interfaces/IPastParticipants.md#pastparticipants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24828](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24828)

Converts this PastParticipants to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:24765](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24765)

Creates a new PastParticipants instance using the specified properties.

#### Parameters

##### properties?

[`IPastParticipants`](../interfaces/IPastParticipants.md)

Properties to set

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:24791](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24791)

Decodes a PastParticipants message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:24800](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24800)

Decodes a PastParticipants message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24773](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24773)

Encodes the specified PastParticipants message. Does not implicitly [verify](PastParticipants.md#verify) messages.

#### Parameters

##### message

[`IPastParticipants`](../interfaces/IPastParticipants.md)

PastParticipants message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24781](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24781)

Encodes the specified PastParticipants message, length delimited. Does not implicitly [verify](PastParticipants.md#verify) messages.

#### Parameters

##### message

[`IPastParticipants`](../interfaces/IPastParticipants.md)

PastParticipants message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:24814](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24814)

Creates a PastParticipants message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:24822](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24822)

Creates a plain object from a PastParticipants message. Also converts values to other types if specified.

#### Parameters

##### message

[`PastParticipants`](PastParticipants.md)

PastParticipants

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24807](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24807)

Verifies a PastParticipants message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
