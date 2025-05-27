# Class: MsgRowOpaqueData

Defined in: [WAProto/index.d.ts:24098](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24098)

Represents a MsgRowOpaqueData.

## Implements

- [`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

## Constructors

### new MsgRowOpaqueData()

> **new MsgRowOpaqueData**(`properties`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:24104](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24104)

Constructs a new MsgRowOpaqueData.

#### Parameters

##### properties?

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

Properties to set

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

## Properties

### currentMsg?

> `optional` **currentMsg**: `null` \| [`IMsgOpaqueData`](../interfaces/IMsgOpaqueData.md)

Defined in: [WAProto/index.d.ts:24107](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24107)

MsgRowOpaqueData currentMsg.

#### Implementation of

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md).[`currentMsg`](../interfaces/IMsgRowOpaqueData.md#currentmsg)

***

### quotedMsg?

> `optional` **quotedMsg**: `null` \| [`IMsgOpaqueData`](../interfaces/IMsgOpaqueData.md)

Defined in: [WAProto/index.d.ts:24110](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24110)

MsgRowOpaqueData quotedMsg.

#### Implementation of

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md).[`quotedMsg`](../interfaces/IMsgRowOpaqueData.md#quotedmsg)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24180](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24180)

Converts this MsgRowOpaqueData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:24117](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24117)

Creates a new MsgRowOpaqueData instance using the specified properties.

#### Parameters

##### properties?

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

Properties to set

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:24143](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24143)

Decodes a MsgRowOpaqueData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:24152](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24152)

Decodes a MsgRowOpaqueData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24125](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24125)

Encodes the specified MsgRowOpaqueData message. Does not implicitly [verify](MsgRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

MsgRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24133](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24133)

Encodes the specified MsgRowOpaqueData message, length delimited. Does not implicitly [verify](MsgRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

MsgRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:24166](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24166)

Creates a MsgRowOpaqueData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:24174](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24174)

Creates a plain object from a MsgRowOpaqueData message. Also converts values to other types if specified.

#### Parameters

##### message

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24159](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24159)

Verifies a MsgRowOpaqueData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
