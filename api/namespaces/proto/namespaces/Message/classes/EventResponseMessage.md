# Class: EventResponseMessage

Defined in: [WAProto/index.d.ts:13555](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13555)

Represents an EventResponseMessage.

## Implements

- [`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

## Constructors

### new EventResponseMessage()

> **new EventResponseMessage**(`properties`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:13561](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13561)

Constructs a new EventResponseMessage.

#### Parameters

##### properties?

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

Properties to set

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

## Properties

### response

> **response**: [`EventResponseType`](../namespaces/EventResponseMessage/enumerations/EventResponseType.md)

Defined in: [WAProto/index.d.ts:13564](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13564)

EventResponseMessage response.

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`response`](../interfaces/IEventResponseMessage.md#response)

***

### timestampMs

> **timestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:13567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13567)

EventResponseMessage timestampMs.

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`timestampMs`](../interfaces/IEventResponseMessage.md#timestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13637](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13637)

Converts this EventResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:13574](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13574)

Creates a new EventResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

Properties to set

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:13600](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13600)

Decodes an EventResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:13609](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13609)

Decodes an EventResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13582](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13582)

Encodes the specified EventResponseMessage message. Does not implicitly [verify](EventResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

EventResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13590](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13590)

Encodes the specified EventResponseMessage message, length delimited. Does not implicitly [verify](EventResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

EventResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:13623](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13623)

Creates an EventResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:13631](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13631)

Creates a plain object from an EventResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13616](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13616)

Verifies an EventResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
