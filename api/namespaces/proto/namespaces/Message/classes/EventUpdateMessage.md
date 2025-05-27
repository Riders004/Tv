# Class: EventUpdateMessage

Defined in: [WAProto/index.d.ts:13661](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13661)

Represents an EventUpdateMessage.

## Implements

- [`IEventUpdateMessage`](../interfaces/IEventUpdateMessage.md)

## Constructors

### new EventUpdateMessage()

> **new EventUpdateMessage**(`properties`?): [`EventUpdateMessage`](EventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13667](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13667)

Constructs a new EventUpdateMessage.

#### Parameters

##### properties?

[`IEventUpdateMessage`](../interfaces/IEventUpdateMessage.md)

Properties to set

#### Returns

[`EventUpdateMessage`](EventUpdateMessage.md)

## Properties

### edit?

> `optional` **edit**: `null` \| [`IEventEditMessage`](../interfaces/IEventEditMessage.md)

Defined in: [WAProto/index.d.ts:13673](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13673)

EventUpdateMessage edit.

#### Implementation of

[`IEventUpdateMessage`](../interfaces/IEventUpdateMessage.md).[`edit`](../interfaces/IEventUpdateMessage.md#edit)

***

### response?

> `optional` **response**: `null` \| [`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:13670](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13670)

EventUpdateMessage response.

#### Implementation of

[`IEventUpdateMessage`](../interfaces/IEventUpdateMessage.md).[`response`](../interfaces/IEventUpdateMessage.md#response)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13743](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13743)

Converts this EventUpdateMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EventUpdateMessage`](EventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13680](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13680)

Creates a new EventUpdateMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEventUpdateMessage`](../interfaces/IEventUpdateMessage.md)

Properties to set

#### Returns

[`EventUpdateMessage`](EventUpdateMessage.md)

EventUpdateMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EventUpdateMessage`](EventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13706](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13706)

Decodes an EventUpdateMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EventUpdateMessage`](EventUpdateMessage.md)

EventUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EventUpdateMessage`](EventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13715)

Decodes an EventUpdateMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EventUpdateMessage`](EventUpdateMessage.md)

EventUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13688](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13688)

Encodes the specified EventUpdateMessage message. Does not implicitly [verify](EventUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IEventUpdateMessage`](../interfaces/IEventUpdateMessage.md)

EventUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13696](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13696)

Encodes the specified EventUpdateMessage message, length delimited. Does not implicitly [verify](EventUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IEventUpdateMessage`](../interfaces/IEventUpdateMessage.md)

EventUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EventUpdateMessage`](EventUpdateMessage.md)

Defined in: [WAProto/index.d.ts:13729](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13729)

Creates an EventUpdateMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EventUpdateMessage`](EventUpdateMessage.md)

EventUpdateMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:13737](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13737)

Creates a plain object from an EventUpdateMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EventUpdateMessage`](EventUpdateMessage.md)

EventUpdateMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13722](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13722)

Verifies an EventUpdateMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
