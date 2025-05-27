# Class: ChatRowOpaqueData

Defined in: [WAProto/index.d.ts:2323](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2323)

Represents a ChatRowOpaqueData.

## Implements

- [`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

## Constructors

### new ChatRowOpaqueData()

> **new ChatRowOpaqueData**(`properties`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2329](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2329)

Constructs a new ChatRowOpaqueData.

#### Parameters

##### properties?

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

Properties to set

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

## Properties

### draftMessage?

> `optional` **draftMessage**: `null` \| [`IDraftMessage`](../namespaces/ChatRowOpaqueData/interfaces/IDraftMessage.md)

Defined in: [WAProto/index.d.ts:2332](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2332)

ChatRowOpaqueData draftMessage.

#### Implementation of

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md).[`draftMessage`](../interfaces/IChatRowOpaqueData.md#draftmessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2402](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2402)

Converts this ChatRowOpaqueData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2339](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2339)

Creates a new ChatRowOpaqueData instance using the specified properties.

#### Parameters

##### properties?

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

Properties to set

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2365](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2365)

Decodes a ChatRowOpaqueData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2374](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2374)

Decodes a ChatRowOpaqueData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2347](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2347)

Encodes the specified ChatRowOpaqueData message. Does not implicitly [verify](ChatRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

ChatRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2355](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2355)

Encodes the specified ChatRowOpaqueData message, length delimited. Does not implicitly [verify](ChatRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

ChatRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2388](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2388)

Creates a ChatRowOpaqueData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:2396](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2396)

Creates a plain object from a ChatRowOpaqueData message. Also converts values to other types if specified.

#### Parameters

##### message

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2381](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2381)

Verifies a ChatRowOpaqueData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
