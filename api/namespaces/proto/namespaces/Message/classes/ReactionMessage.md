# Class: ReactionMessage

Defined in: [WAProto/index.d.ts:21314](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21314)

Represents a ReactionMessage.

## Implements

- [`IReactionMessage`](../interfaces/IReactionMessage.md)

## Constructors

### new ReactionMessage()

> **new ReactionMessage**(`properties`?): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:21320](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21320)

Constructs a new ReactionMessage.

#### Parameters

##### properties?

[`IReactionMessage`](../interfaces/IReactionMessage.md)

Properties to set

#### Returns

[`ReactionMessage`](ReactionMessage.md)

## Properties

### groupingKey

> **groupingKey**: `string`

Defined in: [WAProto/index.d.ts:21329](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21329)

ReactionMessage groupingKey.

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`groupingKey`](../interfaces/IReactionMessage.md#groupingkey)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:21323](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21323)

ReactionMessage key.

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`key`](../interfaces/IReactionMessage.md#key)

***

### senderTimestampMs

> **senderTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:21332](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21332)

ReactionMessage senderTimestampMs.

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`senderTimestampMs`](../interfaces/IReactionMessage.md#sendertimestampms)

***

### text

> **text**: `string`

Defined in: [WAProto/index.d.ts:21326](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21326)

ReactionMessage text.

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`text`](../interfaces/IReactionMessage.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21402](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21402)

Converts this ReactionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:21339](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21339)

Creates a new ReactionMessage instance using the specified properties.

#### Parameters

##### properties?

[`IReactionMessage`](../interfaces/IReactionMessage.md)

Properties to set

#### Returns

[`ReactionMessage`](ReactionMessage.md)

ReactionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:21365](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21365)

Decodes a ReactionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ReactionMessage`](ReactionMessage.md)

ReactionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:21374](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21374)

Decodes a ReactionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ReactionMessage`](ReactionMessage.md)

ReactionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21347](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21347)

Encodes the specified ReactionMessage message. Does not implicitly [verify](ReactionMessage.md#verify) messages.

#### Parameters

##### message

[`IReactionMessage`](../interfaces/IReactionMessage.md)

ReactionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21355](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21355)

Encodes the specified ReactionMessage message, length delimited. Does not implicitly [verify](ReactionMessage.md#verify) messages.

#### Parameters

##### message

[`IReactionMessage`](../interfaces/IReactionMessage.md)

ReactionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:21388](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21388)

Creates a ReactionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ReactionMessage`](ReactionMessage.md)

ReactionMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21396](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21396)

Creates a plain object from a ReactionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ReactionMessage`](ReactionMessage.md)

ReactionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21381](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21381)

Verifies a ReactionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
