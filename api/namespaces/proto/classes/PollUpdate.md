# Class: PollUpdate

Defined in: [WAProto/index.d.ts:26121](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26121)

Represents a PollUpdate.

## Implements

- [`IPollUpdate`](../interfaces/IPollUpdate.md)

## Constructors

### new PollUpdate()

> **new PollUpdate**(`properties`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:26127](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26127)

Constructs a new PollUpdate.

#### Parameters

##### properties?

[`IPollUpdate`](../interfaces/IPollUpdate.md)

Properties to set

#### Returns

[`PollUpdate`](PollUpdate.md)

## Properties

### pollUpdateMessageKey?

> `optional` **pollUpdateMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:26130](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26130)

PollUpdate pollUpdateMessageKey.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`pollUpdateMessageKey`](../interfaces/IPollUpdate.md#pollupdatemessagekey)

***

### senderTimestampMs

> **senderTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:26136](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26136)

PollUpdate senderTimestampMs.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`senderTimestampMs`](../interfaces/IPollUpdate.md#sendertimestampms)

***

### serverTimestampMs

> **serverTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:26139](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26139)

PollUpdate serverTimestampMs.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`serverTimestampMs`](../interfaces/IPollUpdate.md#servertimestampms)

***

### unread

> **unread**: `boolean`

Defined in: [WAProto/index.d.ts:26142](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26142)

PollUpdate unread.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`unread`](../interfaces/IPollUpdate.md#unread)

***

### vote?

> `optional` **vote**: `null` \| [`IPollVoteMessage`](../namespaces/Message/interfaces/IPollVoteMessage.md)

Defined in: [WAProto/index.d.ts:26133](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26133)

PollUpdate vote.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`vote`](../interfaces/IPollUpdate.md#vote)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26212](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26212)

Converts this PollUpdate to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:26149](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26149)

Creates a new PollUpdate instance using the specified properties.

#### Parameters

##### properties?

[`IPollUpdate`](../interfaces/IPollUpdate.md)

Properties to set

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:26175](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26175)

Decodes a PollUpdate message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:26184](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26184)

Decodes a PollUpdate message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26157)

Encodes the specified PollUpdate message. Does not implicitly [verify](PollUpdate.md#verify) messages.

#### Parameters

##### message

[`IPollUpdate`](../interfaces/IPollUpdate.md)

PollUpdate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26165](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26165)

Encodes the specified PollUpdate message, length delimited. Does not implicitly [verify](PollUpdate.md#verify) messages.

#### Parameters

##### message

[`IPollUpdate`](../interfaces/IPollUpdate.md)

PollUpdate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:26198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26198)

Creates a PollUpdate message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:26206](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26206)

Creates a plain object from a PollUpdate message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollUpdate`](PollUpdate.md)

PollUpdate

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26191](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26191)

Verifies a PollUpdate message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
