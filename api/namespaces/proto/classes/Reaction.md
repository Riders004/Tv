# Class: Reaction

Defined in: [WAProto/index.d.ts:27056](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27056)

Represents a Reaction.

## Implements

- [`IReaction`](../interfaces/IReaction.md)

## Constructors

### new Reaction()

> **new Reaction**(`properties`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:27062](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27062)

Constructs a new Reaction.

#### Parameters

##### properties?

[`IReaction`](../interfaces/IReaction.md)

Properties to set

#### Returns

[`Reaction`](Reaction.md)

## Properties

### groupingKey

> **groupingKey**: `string`

Defined in: [WAProto/index.d.ts:27071](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27071)

Reaction groupingKey.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`groupingKey`](../interfaces/IReaction.md#groupingkey)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:27065](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27065)

Reaction key.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`key`](../interfaces/IReaction.md#key)

***

### senderTimestampMs

> **senderTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:27074](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27074)

Reaction senderTimestampMs.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`senderTimestampMs`](../interfaces/IReaction.md#sendertimestampms)

***

### text

> **text**: `string`

Defined in: [WAProto/index.d.ts:27068](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27068)

Reaction text.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`text`](../interfaces/IReaction.md#text)

***

### unread

> **unread**: `boolean`

Defined in: [WAProto/index.d.ts:27077](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27077)

Reaction unread.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`unread`](../interfaces/IReaction.md#unread)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27147](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27147)

Converts this Reaction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:27084](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27084)

Creates a new Reaction instance using the specified properties.

#### Parameters

##### properties?

[`IReaction`](../interfaces/IReaction.md)

Properties to set

#### Returns

[`Reaction`](Reaction.md)

Reaction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:27110](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27110)

Decodes a Reaction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Reaction`](Reaction.md)

Reaction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:27119](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27119)

Decodes a Reaction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Reaction`](Reaction.md)

Reaction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27092)

Encodes the specified Reaction message. Does not implicitly [verify](Reaction.md#verify) messages.

#### Parameters

##### message

[`IReaction`](../interfaces/IReaction.md)

Reaction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27100](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27100)

Encodes the specified Reaction message, length delimited. Does not implicitly [verify](Reaction.md#verify) messages.

#### Parameters

##### message

[`IReaction`](../interfaces/IReaction.md)

Reaction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:27133](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27133)

Creates a Reaction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Reaction`](Reaction.md)

Reaction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27141)

Creates a plain object from a Reaction message. Also converts values to other types if specified.

#### Parameters

##### message

[`Reaction`](Reaction.md)

Reaction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27126](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27126)

Verifies a Reaction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
