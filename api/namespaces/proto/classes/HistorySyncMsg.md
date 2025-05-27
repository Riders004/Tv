# Class: HistorySyncMsg

Defined in: [WAProto/index.d.ts:7652](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7652)

Represents a HistorySyncMsg.

## Implements

- [`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

## Constructors

### new HistorySyncMsg()

> **new HistorySyncMsg**(`properties`?): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:7658](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7658)

Constructs a new HistorySyncMsg.

#### Parameters

##### properties?

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

Properties to set

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IWebMessageInfo`](../interfaces/IWebMessageInfo.md)

Defined in: [WAProto/index.d.ts:7661](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7661)

HistorySyncMsg message.

#### Implementation of

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md).[`message`](../interfaces/IHistorySyncMsg.md#message)

***

### msgOrderId

> **msgOrderId**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:7664](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7664)

HistorySyncMsg msgOrderId.

#### Implementation of

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md).[`msgOrderId`](../interfaces/IHistorySyncMsg.md#msgorderid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7734](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7734)

Converts this HistorySyncMsg to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:7671](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7671)

Creates a new HistorySyncMsg instance using the specified properties.

#### Parameters

##### properties?

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

Properties to set

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

HistorySyncMsg instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:7697](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7697)

Decodes a HistorySyncMsg message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

HistorySyncMsg

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:7706](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7706)

Decodes a HistorySyncMsg message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

HistorySyncMsg

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7679](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7679)

Encodes the specified HistorySyncMsg message. Does not implicitly [verify](HistorySyncMsg.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

HistorySyncMsg message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7687](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7687)

Encodes the specified HistorySyncMsg message, length delimited. Does not implicitly [verify](HistorySyncMsg.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

HistorySyncMsg message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:7720](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7720)

Creates a HistorySyncMsg message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

HistorySyncMsg

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:7728](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7728)

Creates a plain object from a HistorySyncMsg message. Also converts values to other types if specified.

#### Parameters

##### message

[`HistorySyncMsg`](HistorySyncMsg.md)

HistorySyncMsg

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7713](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7713)

Verifies a HistorySyncMsg message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
