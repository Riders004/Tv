# Class: UnarchiveChatsSetting

Defined in: [WAProto/index.d.ts:34099](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34099)

Represents an UnarchiveChatsSetting.

## Implements

- [`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

## Constructors

### new UnarchiveChatsSetting()

> **new UnarchiveChatsSetting**(`properties`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:34105](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34105)

Constructs a new UnarchiveChatsSetting.

#### Parameters

##### properties?

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

Properties to set

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

## Properties

### unarchiveChats

> **unarchiveChats**: `boolean`

Defined in: [WAProto/index.d.ts:34108](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34108)

UnarchiveChatsSetting unarchiveChats.

#### Implementation of

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md).[`unarchiveChats`](../interfaces/IUnarchiveChatsSetting.md#unarchivechats)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34178](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34178)

Converts this UnarchiveChatsSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:34115](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34115)

Creates a new UnarchiveChatsSetting instance using the specified properties.

#### Parameters

##### properties?

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

Properties to set

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:34141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34141)

Decodes an UnarchiveChatsSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:34150](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34150)

Decodes an UnarchiveChatsSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34123](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34123)

Encodes the specified UnarchiveChatsSetting message. Does not implicitly [verify](UnarchiveChatsSetting.md#verify) messages.

#### Parameters

##### message

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

UnarchiveChatsSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34131](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34131)

Encodes the specified UnarchiveChatsSetting message, length delimited. Does not implicitly [verify](UnarchiveChatsSetting.md#verify) messages.

#### Parameters

##### message

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

UnarchiveChatsSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:34164](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34164)

Creates an UnarchiveChatsSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34172](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34172)

Creates a plain object from an UnarchiveChatsSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34157)

Verifies an UnarchiveChatsSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
