# Class: PollUpdateMessageMetadata

Defined in: [WAProto/index.d.ts:20538](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20538)

Represents a PollUpdateMessageMetadata.

## Implements

- [`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

## Constructors

### new PollUpdateMessageMetadata()

> **new PollUpdateMessageMetadata**(`properties`?): [`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:20544](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20544)

Constructs a new PollUpdateMessageMetadata.

#### Parameters

##### properties?

[`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

Properties to set

#### Returns

[`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20614](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20614)

Converts this PollUpdateMessageMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:20551](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20551)

Creates a new PollUpdateMessageMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

Properties to set

#### Returns

[`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

PollUpdateMessageMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:20577](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20577)

Decodes a PollUpdateMessageMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

PollUpdateMessageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:20586](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20586)

Decodes a PollUpdateMessageMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

PollUpdateMessageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20559](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20559)

Encodes the specified PollUpdateMessageMetadata message. Does not implicitly [verify](PollUpdateMessageMetadata.md#verify) messages.

#### Parameters

##### message

[`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

PollUpdateMessageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20567)

Encodes the specified PollUpdateMessageMetadata message, length delimited. Does not implicitly [verify](PollUpdateMessageMetadata.md#verify) messages.

#### Parameters

##### message

[`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

PollUpdateMessageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:20600](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20600)

Creates a PollUpdateMessageMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

PollUpdateMessageMetadata

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20608](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20608)

Creates a plain object from a PollUpdateMessageMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollUpdateMessageMetadata`](PollUpdateMessageMetadata.md)

PollUpdateMessageMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20593](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20593)

Verifies a PollUpdateMessageMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
