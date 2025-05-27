# Class: EncEventUpdateMessage

Defined in: [WAProto/index.d.ts:13132](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13132)

Represents an EncEventUpdateMessage.

## Implements

- [`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md)

## Constructors

### new EncEventUpdateMessage()

> **new EncEventUpdateMessage**(`properties`?): [`EncEventUpdateMessage`](EncEventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13138](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13138)

Constructs a new EncEventUpdateMessage.

#### Parameters

##### properties?

[`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md)

Properties to set

#### Returns

[`EncEventUpdateMessage`](EncEventUpdateMessage.md)

## Properties

### encIv

> **encIv**: `Uint8Array`

Defined in: [WAProto/index.d.ts:13147](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13147)

EncEventUpdateMessage encIv.

#### Implementation of

[`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md).[`encIv`](../interfaces/IEncEventUpdateMessage.md#enciv)

***

### encPayload

> **encPayload**: `Uint8Array`

Defined in: [WAProto/index.d.ts:13144](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13144)

EncEventUpdateMessage encPayload.

#### Implementation of

[`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md).[`encPayload`](../interfaces/IEncEventUpdateMessage.md#encpayload)

***

### eventCreationMessageKey?

> `optional` **eventCreationMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:13141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13141)

EncEventUpdateMessage eventCreationMessageKey.

#### Implementation of

[`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md).[`eventCreationMessageKey`](../interfaces/IEncEventUpdateMessage.md#eventcreationmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13217](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13217)

Converts this EncEventUpdateMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EncEventUpdateMessage`](EncEventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13154](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13154)

Creates a new EncEventUpdateMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md)

Properties to set

#### Returns

[`EncEventUpdateMessage`](EncEventUpdateMessage.md)

EncEventUpdateMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EncEventUpdateMessage`](EncEventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13180](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13180)

Decodes an EncEventUpdateMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EncEventUpdateMessage`](EncEventUpdateMessage.md)

EncEventUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EncEventUpdateMessage`](EncEventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13189](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13189)

Decodes an EncEventUpdateMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EncEventUpdateMessage`](EncEventUpdateMessage.md)

EncEventUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13162](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13162)

Encodes the specified EncEventUpdateMessage message. Does not implicitly [verify](EncEventUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md)

EncEventUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13170](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13170)

Encodes the specified EncEventUpdateMessage message, length delimited. Does not implicitly [verify](EncEventUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IEncEventUpdateMessage`](../interfaces/IEncEventUpdateMessage.md)

EncEventUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EncEventUpdateMessage`](EncEventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13203](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13203)

Creates an EncEventUpdateMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EncEventUpdateMessage`](EncEventUpdateMessage.md)

EncEventUpdateMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:13211](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13211)

Creates a plain object from an EncEventUpdateMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EncEventUpdateMessage`](EncEventUpdateMessage.md)

EncEventUpdateMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13196](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13196)

Verifies an EncEventUpdateMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
