# Class: EventMessage

Defined in: [WAProto/index.d.ts:13444](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13444)

Represents an EventMessage.

## Implements

- [`IEventMessage`](../interfaces/IEventMessage.md)

## Constructors

### new EventMessage()

> **new EventMessage**(`properties`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:13450](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13450)

Constructs a new EventMessage.

#### Parameters

##### properties?

[`IEventMessage`](../interfaces/IEventMessage.md)

Properties to set

#### Returns

[`EventMessage`](EventMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:13453](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13453)

EventMessage contextInfo.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`contextInfo`](../interfaces/IEventMessage.md#contextinfo)

***

### description

> **description**: `string`

Defined in: [WAProto/index.d.ts:13462](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13462)

EventMessage description.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`description`](../interfaces/IEventMessage.md#description)

***

### isCanceled

> **isCanceled**: `boolean`

Defined in: [WAProto/index.d.ts:13456](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13456)

EventMessage isCanceled.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`isCanceled`](../interfaces/IEventMessage.md#iscanceled)

***

### joinLink

> **joinLink**: `string`

Defined in: [WAProto/index.d.ts:13468](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13468)

EventMessage joinLink.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`joinLink`](../interfaces/IEventMessage.md#joinlink)

***

### location?

> `optional` **location**: `null` \| [`ILocationMessage`](../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:13465](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13465)

EventMessage location.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`location`](../interfaces/IEventMessage.md#location)

***

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:13459](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13459)

EventMessage name.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`name`](../interfaces/IEventMessage.md#name)

***

### startTime

> **startTime**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:13471](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13471)

EventMessage startTime.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`startTime`](../interfaces/IEventMessage.md#starttime)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13541)

Converts this EventMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:13478](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13478)

Creates a new EventMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEventMessage`](../interfaces/IEventMessage.md)

Properties to set

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:13504](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13504)

Decodes an EventMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:13513](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13513)

Decodes an EventMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13486](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13486)

Encodes the specified EventMessage message. Does not implicitly [verify](EventMessage.md#verify) messages.

#### Parameters

##### message

[`IEventMessage`](../interfaces/IEventMessage.md)

EventMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13494](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13494)

Encodes the specified EventMessage message, length delimited. Does not implicitly [verify](EventMessage.md#verify) messages.

#### Parameters

##### message

[`IEventMessage`](../interfaces/IEventMessage.md)

EventMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:13527](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13527)

Creates an EventMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:13535](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13535)

Creates a plain object from an EventMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EventMessage`](EventMessage.md)

EventMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13520](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L13520)

Verifies an EventMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
