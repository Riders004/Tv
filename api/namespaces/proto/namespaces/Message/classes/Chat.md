# Class: Chat

Defined in: [WAProto/index.d.ts:12235](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12235)

Represents a Chat.

## Implements

- [`IChat`](../interfaces/IChat.md)

## Constructors

### new Chat()

> **new Chat**(`properties`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:12241](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12241)

Constructs a new Chat.

#### Parameters

##### properties?

[`IChat`](../interfaces/IChat.md)

Properties to set

#### Returns

[`Chat`](Chat.md)

## Properties

### displayName

> **displayName**: `string`

Defined in: [WAProto/index.d.ts:12244](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12244)

Chat displayName.

#### Implementation of

[`IChat`](../interfaces/IChat.md).[`displayName`](../interfaces/IChat.md#displayname)

***

### id

> **id**: `string`

Defined in: [WAProto/index.d.ts:12247](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12247)

Chat id.

#### Implementation of

[`IChat`](../interfaces/IChat.md).[`id`](../interfaces/IChat.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12317](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12317)

Converts this Chat to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:12254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12254)

Creates a new Chat instance using the specified properties.

#### Parameters

##### properties?

[`IChat`](../interfaces/IChat.md)

Properties to set

#### Returns

[`Chat`](Chat.md)

Chat instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:12280](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12280)

Decodes a Chat message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Chat`](Chat.md)

Chat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:12289](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12289)

Decodes a Chat message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Chat`](Chat.md)

Chat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12262)

Encodes the specified Chat message. Does not implicitly [verify](Chat.md#verify) messages.

#### Parameters

##### message

[`IChat`](../interfaces/IChat.md)

Chat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12270](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12270)

Encodes the specified Chat message, length delimited. Does not implicitly [verify](Chat.md#verify) messages.

#### Parameters

##### message

[`IChat`](../interfaces/IChat.md)

Chat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:12303](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12303)

Creates a Chat message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Chat`](Chat.md)

Chat

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12311](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12311)

Creates a plain object from a Chat message. Also converts values to other types if specified.

#### Parameters

##### message

[`Chat`](Chat.md)

Chat

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12296](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12296)

Verifies a Chat message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
