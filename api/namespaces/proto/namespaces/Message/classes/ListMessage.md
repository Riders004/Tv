# Class: ListMessage

Defined in: [WAProto/index.d.ts:17085](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17085)

Represents a ListMessage.

## Implements

- [`IListMessage`](../interfaces/IListMessage.md)

## Constructors

### new ListMessage()

> **new ListMessage**(`properties`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:17091](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17091)

Constructs a new ListMessage.

#### Parameters

##### properties?

[`IListMessage`](../interfaces/IListMessage.md)

Properties to set

#### Returns

[`ListMessage`](ListMessage.md)

## Properties

### buttonText

> **buttonText**: `string`

Defined in: [WAProto/index.d.ts:17100](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17100)

ListMessage buttonText.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`buttonText`](../interfaces/IListMessage.md#buttontext)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:17115](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17115)

ListMessage contextInfo.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`contextInfo`](../interfaces/IListMessage.md#contextinfo)

***

### description

> **description**: `string`

Defined in: [WAProto/index.d.ts:17097](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17097)

ListMessage description.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`description`](../interfaces/IListMessage.md#description)

***

### footerText

> **footerText**: `string`

Defined in: [WAProto/index.d.ts:17112](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17112)

ListMessage footerText.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`footerText`](../interfaces/IListMessage.md#footertext)

***

### listType

> **listType**: [`ListType`](../namespaces/ListMessage/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:17103](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17103)

ListMessage listType.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`listType`](../interfaces/IListMessage.md#listtype)

***

### productListInfo?

> `optional` **productListInfo**: `null` \| [`IProductListInfo`](../namespaces/ListMessage/interfaces/IProductListInfo.md)

Defined in: [WAProto/index.d.ts:17109](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17109)

ListMessage productListInfo.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`productListInfo`](../interfaces/IListMessage.md#productlistinfo)

***

### sections

> **sections**: [`ISection`](../namespaces/ListMessage/interfaces/ISection.md)[]

Defined in: [WAProto/index.d.ts:17106](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17106)

ListMessage sections.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`sections`](../interfaces/IListMessage.md#sections)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:17094](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17094)

ListMessage title.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`title`](../interfaces/IListMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17185](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17185)

Converts this ListMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:17122](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17122)

Creates a new ListMessage instance using the specified properties.

#### Parameters

##### properties?

[`IListMessage`](../interfaces/IListMessage.md)

Properties to set

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:17148](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17148)

Decodes a ListMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:17157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17157)

Decodes a ListMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17130](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17130)

Encodes the specified ListMessage message. Does not implicitly [verify](ListMessage.md#verify) messages.

#### Parameters

##### message

[`IListMessage`](../interfaces/IListMessage.md)

ListMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17138](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17138)

Encodes the specified ListMessage message, length delimited. Does not implicitly [verify](ListMessage.md#verify) messages.

#### Parameters

##### message

[`IListMessage`](../interfaces/IListMessage.md)

ListMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:17171](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17171)

Creates a ListMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17179](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17179)

Creates a plain object from a ListMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ListMessage`](ListMessage.md)

ListMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17164](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17164)

Verifies a ListMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
