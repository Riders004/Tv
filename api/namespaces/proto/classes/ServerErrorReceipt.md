# Class: ServerErrorReceipt

Defined in: [WAProto/index.d.ts:28139](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28139)

Represents a ServerErrorReceipt.

## Implements

- [`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

## Constructors

### new ServerErrorReceipt()

> **new ServerErrorReceipt**(`properties`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:28145](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28145)

Constructs a new ServerErrorReceipt.

#### Parameters

##### properties?

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

Properties to set

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

## Properties

### stanzaId

> **stanzaId**: `string`

Defined in: [WAProto/index.d.ts:28148](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28148)

ServerErrorReceipt stanzaId.

#### Implementation of

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md).[`stanzaId`](../interfaces/IServerErrorReceipt.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28218](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28218)

Converts this ServerErrorReceipt to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:28155](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28155)

Creates a new ServerErrorReceipt instance using the specified properties.

#### Parameters

##### properties?

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

Properties to set

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:28181](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28181)

Decodes a ServerErrorReceipt message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:28190](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28190)

Decodes a ServerErrorReceipt message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28163](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28163)

Encodes the specified ServerErrorReceipt message. Does not implicitly [verify](ServerErrorReceipt.md#verify) messages.

#### Parameters

##### message

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

ServerErrorReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28171](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28171)

Encodes the specified ServerErrorReceipt message, length delimited. Does not implicitly [verify](ServerErrorReceipt.md#verify) messages.

#### Parameters

##### message

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

ServerErrorReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:28204](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28204)

Creates a ServerErrorReceipt message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28212](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28212)

Creates a plain object from a ServerErrorReceipt message. Also converts values to other types if specified.

#### Parameters

##### message

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28197](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28197)

Verifies a ServerErrorReceipt message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
