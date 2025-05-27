# Class: EventEditMessage

Defined in: [WAProto/index.d.ts:13333](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13333)

Represents an EventEditMessage.

## Implements

- [`IEventEditMessage`](../interfaces/IEventEditMessage.md)

## Constructors

### new EventEditMessage()

> **new EventEditMessage**(`properties`?): [`EventEditMessage`](EventEditMessage.md)

Defined in: [WAProto/index.d.ts:13339](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13339)

Constructs a new EventEditMessage.

#### Parameters

##### properties?

[`IEventEditMessage`](../interfaces/IEventEditMessage.md)

Properties to set

#### Returns

[`EventEditMessage`](EventEditMessage.md)

## Properties

### editTimestampMs

> **editTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:13345](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13345)

EventEditMessage editTimestampMs.

#### Implementation of

[`IEventEditMessage`](../interfaces/IEventEditMessage.md).[`editTimestampMs`](../interfaces/IEventEditMessage.md#edittimestampms)

***

### eventEditMessage?

> `optional` **eventEditMessage**: `null` \| [`IEventMessage`](../interfaces/IEventMessage.md)

Defined in: [WAProto/index.d.ts:13342](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13342)

EventEditMessage eventEditMessage.

#### Implementation of

[`IEventEditMessage`](../interfaces/IEventEditMessage.md).[`eventEditMessage`](../interfaces/IEventEditMessage.md#eventeditmessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13415](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13415)

Converts this EventEditMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EventEditMessage`](EventEditMessage.md)

Defined in: [WAProto/index.d.ts:13352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13352)

Creates a new EventEditMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEventEditMessage`](../interfaces/IEventEditMessage.md)

Properties to set

#### Returns

[`EventEditMessage`](EventEditMessage.md)

EventEditMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EventEditMessage`](EventEditMessage.md)

Defined in: [WAProto/index.d.ts:13378](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13378)

Decodes an EventEditMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EventEditMessage`](EventEditMessage.md)

EventEditMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EventEditMessage`](EventEditMessage.md)

Defined in: [WAProto/index.d.ts:13387](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13387)

Decodes an EventEditMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EventEditMessage`](EventEditMessage.md)

EventEditMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13360](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13360)

Encodes the specified EventEditMessage message. Does not implicitly [verify](EventEditMessage.md#verify) messages.

#### Parameters

##### message

[`IEventEditMessage`](../interfaces/IEventEditMessage.md)

EventEditMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13368](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13368)

Encodes the specified EventEditMessage message, length delimited. Does not implicitly [verify](EventEditMessage.md#verify) messages.

#### Parameters

##### message

[`IEventEditMessage`](../interfaces/IEventEditMessage.md)

EventEditMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EventEditMessage`](EventEditMessage.md)

Defined in: [WAProto/index.d.ts:13401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13401)

Creates an EventEditMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EventEditMessage`](EventEditMessage.md)

EventEditMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:13409](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13409)

Creates a plain object from an EventEditMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EventEditMessage`](EventEditMessage.md)

EventEditMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13394](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13394)

Verifies an EventEditMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
