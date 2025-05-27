# Class: HandshakeMessage

Defined in: [WAProto/index.d.ts:7062](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7062)

Represents a HandshakeMessage.

## Implements

- [`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

## Constructors

### new HandshakeMessage()

> **new HandshakeMessage**(`properties`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:7068](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7068)

Constructs a new HandshakeMessage.

#### Parameters

##### properties?

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

Properties to set

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

## Properties

### clientFinish?

> `optional` **clientFinish**: `null` \| [`IClientFinish`](../namespaces/HandshakeMessage/interfaces/IClientFinish.md)

Defined in: [WAProto/index.d.ts:7077](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7077)

HandshakeMessage clientFinish.

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`clientFinish`](../interfaces/IHandshakeMessage.md#clientfinish)

***

### clientHello?

> `optional` **clientHello**: `null` \| [`IClientHello`](../namespaces/HandshakeMessage/interfaces/IClientHello.md)

Defined in: [WAProto/index.d.ts:7071](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7071)

HandshakeMessage clientHello.

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`clientHello`](../interfaces/IHandshakeMessage.md#clienthello)

***

### serverHello?

> `optional` **serverHello**: `null` \| [`IServerHello`](../namespaces/HandshakeMessage/interfaces/IServerHello.md)

Defined in: [WAProto/index.d.ts:7074](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7074)

HandshakeMessage serverHello.

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`serverHello`](../interfaces/IHandshakeMessage.md#serverhello)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7147](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7147)

Converts this HandshakeMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:7084](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7084)

Creates a new HandshakeMessage instance using the specified properties.

#### Parameters

##### properties?

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

Properties to set

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:7110](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7110)

Decodes a HandshakeMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:7119](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7119)

Decodes a HandshakeMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7092)

Encodes the specified HandshakeMessage message. Does not implicitly [verify](HandshakeMessage.md#verify) messages.

#### Parameters

##### message

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

HandshakeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7100](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7100)

Encodes the specified HandshakeMessage message, length delimited. Does not implicitly [verify](HandshakeMessage.md#verify) messages.

#### Parameters

##### message

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

HandshakeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:7133](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7133)

Creates a HandshakeMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:7141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7141)

Creates a plain object from a HandshakeMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7126](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7126)

Verifies a HandshakeMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
