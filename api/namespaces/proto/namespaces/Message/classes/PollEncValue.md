# Class: PollEncValue

Defined in: [WAProto/index.d.ts:20340](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20340)

Represents a PollEncValue.

## Implements

- [`IPollEncValue`](../interfaces/IPollEncValue.md)

## Constructors

### new PollEncValue()

> **new PollEncValue**(`properties`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:20346](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20346)

Constructs a new PollEncValue.

#### Parameters

##### properties?

[`IPollEncValue`](../interfaces/IPollEncValue.md)

Properties to set

#### Returns

[`PollEncValue`](PollEncValue.md)

## Properties

### encIv

> **encIv**: `Uint8Array`

Defined in: [WAProto/index.d.ts:20352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20352)

PollEncValue encIv.

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encIv`](../interfaces/IPollEncValue.md#enciv)

***

### encPayload

> **encPayload**: `Uint8Array`

Defined in: [WAProto/index.d.ts:20349](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20349)

PollEncValue encPayload.

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encPayload`](../interfaces/IPollEncValue.md#encpayload)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20422](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20422)

Converts this PollEncValue to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:20359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20359)

Creates a new PollEncValue instance using the specified properties.

#### Parameters

##### properties?

[`IPollEncValue`](../interfaces/IPollEncValue.md)

Properties to set

#### Returns

[`PollEncValue`](PollEncValue.md)

PollEncValue instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:20385](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20385)

Decodes a PollEncValue message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollEncValue`](PollEncValue.md)

PollEncValue

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:20394](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20394)

Decodes a PollEncValue message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollEncValue`](PollEncValue.md)

PollEncValue

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20367](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20367)

Encodes the specified PollEncValue message. Does not implicitly [verify](PollEncValue.md#verify) messages.

#### Parameters

##### message

[`IPollEncValue`](../interfaces/IPollEncValue.md)

PollEncValue message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20375](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20375)

Encodes the specified PollEncValue message, length delimited. Does not implicitly [verify](PollEncValue.md#verify) messages.

#### Parameters

##### message

[`IPollEncValue`](../interfaces/IPollEncValue.md)

PollEncValue message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:20408](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20408)

Creates a PollEncValue message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollEncValue`](PollEncValue.md)

PollEncValue

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20416](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20416)

Creates a plain object from a PollEncValue message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollEncValue`](PollEncValue.md)

PollEncValue

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20401)

Verifies a PollEncValue message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
