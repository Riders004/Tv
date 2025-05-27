# Class: PollUpdateMessage

Defined in: [WAProto/index.d.ts:20442](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20442)

Represents a PollUpdateMessage.

## Implements

- [`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

## Constructors

### new PollUpdateMessage()

> **new PollUpdateMessage**(`properties`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:20448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20448)

Constructs a new PollUpdateMessage.

#### Parameters

##### properties?

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

Properties to set

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

## Properties

### metadata?

> `optional` **metadata**: `null` \| [`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:20457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20457)

PollUpdateMessage metadata.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`metadata`](../interfaces/IPollUpdateMessage.md#metadata)

***

### pollCreationMessageKey?

> `optional` **pollCreationMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:20451](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20451)

PollUpdateMessage pollCreationMessageKey.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`pollCreationMessageKey`](../interfaces/IPollUpdateMessage.md#pollcreationmessagekey)

***

### senderTimestampMs

> **senderTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:20460](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20460)

PollUpdateMessage senderTimestampMs.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`senderTimestampMs`](../interfaces/IPollUpdateMessage.md#sendertimestampms)

***

### vote?

> `optional` **vote**: `null` \| [`IPollEncValue`](../interfaces/IPollEncValue.md)

Defined in: [WAProto/index.d.ts:20454](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20454)

PollUpdateMessage vote.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`vote`](../interfaces/IPollUpdateMessage.md#vote)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20530](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20530)

Converts this PollUpdateMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:20467](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20467)

Creates a new PollUpdateMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

Properties to set

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:20493](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20493)

Decodes a PollUpdateMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:20502](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20502)

Decodes a PollUpdateMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20475](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20475)

Encodes the specified PollUpdateMessage message. Does not implicitly [verify](PollUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

PollUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20483](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20483)

Encodes the specified PollUpdateMessage message, length delimited. Does not implicitly [verify](PollUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

PollUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:20516](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20516)

Creates a PollUpdateMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20524](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20524)

Creates a plain object from a PollUpdateMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20509](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20509)

Verifies a PollUpdateMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
