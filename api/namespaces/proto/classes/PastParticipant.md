# Class: PastParticipant

Defined in: [WAProto/index.d.ts:24638](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24638)

Represents a PastParticipant.

## Implements

- [`IPastParticipant`](../interfaces/IPastParticipant.md)

## Constructors

### new PastParticipant()

> **new PastParticipant**(`properties`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:24644](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24644)

Constructs a new PastParticipant.

#### Parameters

##### properties?

[`IPastParticipant`](../interfaces/IPastParticipant.md)

Properties to set

#### Returns

[`PastParticipant`](PastParticipant.md)

## Properties

### leaveReason

> **leaveReason**: [`LeaveReason`](../namespaces/PastParticipant/enumerations/LeaveReason.md)

Defined in: [WAProto/index.d.ts:24650](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24650)

PastParticipant leaveReason.

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`leaveReason`](../interfaces/IPastParticipant.md#leavereason)

***

### leaveTs

> **leaveTs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:24653](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24653)

PastParticipant leaveTs.

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`leaveTs`](../interfaces/IPastParticipant.md#leavets)

***

### userJid

> **userJid**: `string`

Defined in: [WAProto/index.d.ts:24647](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24647)

PastParticipant userJid.

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`userJid`](../interfaces/IPastParticipant.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24723](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24723)

Converts this PastParticipant to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:24660](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24660)

Creates a new PastParticipant instance using the specified properties.

#### Parameters

##### properties?

[`IPastParticipant`](../interfaces/IPastParticipant.md)

Properties to set

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:24686](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24686)

Decodes a PastParticipant message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:24695](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24695)

Decodes a PastParticipant message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24668](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24668)

Encodes the specified PastParticipant message. Does not implicitly [verify](PastParticipant.md#verify) messages.

#### Parameters

##### message

[`IPastParticipant`](../interfaces/IPastParticipant.md)

PastParticipant message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24676](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24676)

Encodes the specified PastParticipant message, length delimited. Does not implicitly [verify](PastParticipant.md#verify) messages.

#### Parameters

##### message

[`IPastParticipant`](../interfaces/IPastParticipant.md)

PastParticipant message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:24709](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24709)

Creates a PastParticipant message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:24717](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24717)

Creates a plain object from a PastParticipant message. Also converts values to other types if specified.

#### Parameters

##### message

[`PastParticipant`](PastParticipant.md)

PastParticipant

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24702](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24702)

Verifies a PastParticipant message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
