# Class: ListResponseMessage

Defined in: [WAProto/index.d.ts:17800](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17800)

Represents a ListResponseMessage.

## Implements

- [`IListResponseMessage`](../interfaces/IListResponseMessage.md)

## Constructors

### new ListResponseMessage()

> **new ListResponseMessage**(`properties`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:17806](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17806)

Constructs a new ListResponseMessage.

#### Parameters

##### properties?

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

Properties to set

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:17818](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17818)

ListResponseMessage contextInfo.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`contextInfo`](../interfaces/IListResponseMessage.md#contextinfo)

***

### description

> **description**: `string`

Defined in: [WAProto/index.d.ts:17821](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17821)

ListResponseMessage description.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`description`](../interfaces/IListResponseMessage.md#description)

***

### listType

> **listType**: [`ListType`](../namespaces/ListResponseMessage/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:17812](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17812)

ListResponseMessage listType.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`listType`](../interfaces/IListResponseMessage.md#listtype)

***

### singleSelectReply?

> `optional` **singleSelectReply**: `null` \| [`ISingleSelectReply`](../namespaces/ListResponseMessage/interfaces/ISingleSelectReply.md)

Defined in: [WAProto/index.d.ts:17815](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17815)

ListResponseMessage singleSelectReply.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`singleSelectReply`](../interfaces/IListResponseMessage.md#singleselectreply)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:17809](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17809)

ListResponseMessage title.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`title`](../interfaces/IListResponseMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17891](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17891)

Converts this ListResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:17828](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17828)

Creates a new ListResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

Properties to set

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:17854](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17854)

Decodes a ListResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:17863](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17863)

Decodes a ListResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17836](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17836)

Encodes the specified ListResponseMessage message. Does not implicitly [verify](ListResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

ListResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17844](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17844)

Encodes the specified ListResponseMessage message, length delimited. Does not implicitly [verify](ListResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

ListResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:17877](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17877)

Creates a ListResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17885](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17885)

Creates a plain object from a ListResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17870)

Verifies a ListResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
