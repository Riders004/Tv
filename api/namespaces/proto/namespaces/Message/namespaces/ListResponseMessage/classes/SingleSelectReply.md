# Class: SingleSelectReply

Defined in: [WAProto/index.d.ts:17910](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17910)

Represents a SingleSelectReply.

## Implements

- [`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

## Constructors

### new SingleSelectReply()

> **new SingleSelectReply**(`properties`?): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:17916](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17916)

Constructs a new SingleSelectReply.

#### Parameters

##### properties?

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

Properties to set

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

## Properties

### selectedRowId

> **selectedRowId**: `string`

Defined in: [WAProto/index.d.ts:17919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17919)

SingleSelectReply selectedRowId.

#### Implementation of

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md).[`selectedRowId`](../interfaces/ISingleSelectReply.md#selectedrowid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17989](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17989)

Converts this SingleSelectReply to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:17926](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17926)

Creates a new SingleSelectReply instance using the specified properties.

#### Parameters

##### properties?

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

Properties to set

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

SingleSelectReply instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:17952](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17952)

Decodes a SingleSelectReply message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

SingleSelectReply

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:17961](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17961)

Decodes a SingleSelectReply message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

SingleSelectReply

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17934](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17934)

Encodes the specified SingleSelectReply message. Does not implicitly [verify](SingleSelectReply.md#verify) messages.

#### Parameters

##### message

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

SingleSelectReply message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17942](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17942)

Encodes the specified SingleSelectReply message, length delimited. Does not implicitly [verify](SingleSelectReply.md#verify) messages.

#### Parameters

##### message

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

SingleSelectReply message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:17975](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17975)

Creates a SingleSelectReply message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

SingleSelectReply

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17983](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17983)

Creates a plain object from a SingleSelectReply message. Also converts values to other types if specified.

#### Parameters

##### message

[`SingleSelectReply`](SingleSelectReply.md)

SingleSelectReply

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17968](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17968)

Verifies a SingleSelectReply message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
