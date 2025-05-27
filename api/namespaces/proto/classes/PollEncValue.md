# Class: PollEncValue

Defined in: [WAProto/index.d.ts:26016](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26016)

Represents a PollEncValue.

## Implements

- [`IPollEncValue`](../interfaces/IPollEncValue.md)

## Constructors

### new PollEncValue()

> **new PollEncValue**(`properties`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:26022](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26022)

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

Defined in: [WAProto/index.d.ts:26028](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26028)

PollEncValue encIv.

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encIv`](../interfaces/IPollEncValue.md#enciv)

***

### encPayload

> **encPayload**: `Uint8Array`

Defined in: [WAProto/index.d.ts:26025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26025)

PollEncValue encPayload.

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encPayload`](../interfaces/IPollEncValue.md#encpayload)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26098](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26098)

Converts this PollEncValue to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:26035](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26035)

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

Defined in: [WAProto/index.d.ts:26061](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26061)

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

Defined in: [WAProto/index.d.ts:26070](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26070)

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

Defined in: [WAProto/index.d.ts:26043](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26043)

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

Defined in: [WAProto/index.d.ts:26051](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26051)

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

Defined in: [WAProto/index.d.ts:26084](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26084)

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

Defined in: [WAProto/index.d.ts:26092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26092)

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

Defined in: [WAProto/index.d.ts:26077](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26077)

Verifies a PollEncValue message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
