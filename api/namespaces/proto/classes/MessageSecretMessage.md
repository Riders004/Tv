# Class: MessageSecretMessage

Defined in: [WAProto/index.d.ts:23540](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23540)

Represents a MessageSecretMessage.

## Implements

- [`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

## Constructors

### new MessageSecretMessage()

> **new MessageSecretMessage**(`properties`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:23546](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23546)

Constructs a new MessageSecretMessage.

#### Parameters

##### properties?

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

Properties to set

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

## Properties

### encIv

> **encIv**: `Uint8Array`

Defined in: [WAProto/index.d.ts:23552](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23552)

MessageSecretMessage encIv.

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`encIv`](../interfaces/IMessageSecretMessage.md#enciv)

***

### encPayload

> **encPayload**: `Uint8Array`

Defined in: [WAProto/index.d.ts:23555](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23555)

MessageSecretMessage encPayload.

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`encPayload`](../interfaces/IMessageSecretMessage.md#encpayload)

***

### version

> **version**: `number`

Defined in: [WAProto/index.d.ts:23549](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23549)

MessageSecretMessage version.

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`version`](../interfaces/IMessageSecretMessage.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23625)

Converts this MessageSecretMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:23562](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23562)

Creates a new MessageSecretMessage instance using the specified properties.

#### Parameters

##### properties?

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

Properties to set

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:23588](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23588)

Decodes a MessageSecretMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:23597](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23597)

Decodes a MessageSecretMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23570](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23570)

Encodes the specified MessageSecretMessage message. Does not implicitly [verify](MessageSecretMessage.md#verify) messages.

#### Parameters

##### message

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

MessageSecretMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23578)

Encodes the specified MessageSecretMessage message, length delimited. Does not implicitly [verify](MessageSecretMessage.md#verify) messages.

#### Parameters

##### message

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

MessageSecretMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:23611](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23611)

Creates a MessageSecretMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:23619](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23619)

Creates a plain object from a MessageSecretMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23604)

Verifies a MessageSecretMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
