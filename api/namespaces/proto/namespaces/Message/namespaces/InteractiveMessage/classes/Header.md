# Class: Header

Defined in: [WAProto/index.d.ts:16065](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16065)

Represents a Header.

## Implements

- [`IHeader`](../interfaces/IHeader.md)

## Constructors

### new Header()

> **new Header**(`properties`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:16071](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16071)

Constructs a new Header.

#### Parameters

##### properties?

[`IHeader`](../interfaces/IHeader.md)

Properties to set

#### Returns

[`Header`](Header.md)

## Properties

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../../../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:16083](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16083)

Header documentMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`documentMessage`](../interfaces/IHeader.md#documentmessage)

***

### hasMediaAttachment

> **hasMediaAttachment**: `boolean`

Defined in: [WAProto/index.d.ts:16080](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16080)

Header hasMediaAttachment.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`hasMediaAttachment`](../interfaces/IHeader.md#hasmediaattachment)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:16086](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16086)

Header imageMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`imageMessage`](../interfaces/IHeader.md#imagemessage)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:16089](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16089)

Header jpegThumbnail.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`jpegThumbnail`](../interfaces/IHeader.md#jpegthumbnail)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../../../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:16095](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16095)

Header locationMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`locationMessage`](../interfaces/IHeader.md#locationmessage)

***

### media?

> `optional` **media**: `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"` \| `"jpegThumbnail"`

Defined in: [WAProto/index.d.ts:16098](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16098)

Header media.

***

### subtitle

> **subtitle**: `string`

Defined in: [WAProto/index.d.ts:16077](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16077)

Header subtitle.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`subtitle`](../interfaces/IHeader.md#subtitle)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:16074](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16074)

Header title.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`title`](../interfaces/IHeader.md#title)

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../../../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:16092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16092)

Header videoMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`videoMessage`](../interfaces/IHeader.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16168](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16168)

Converts this Header to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:16105](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16105)

Creates a new Header instance using the specified properties.

#### Parameters

##### properties?

[`IHeader`](../interfaces/IHeader.md)

Properties to set

#### Returns

[`Header`](Header.md)

Header instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:16131](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16131)

Decodes a Header message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Header`](Header.md)

Header

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:16140](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16140)

Decodes a Header message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Header`](Header.md)

Header

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16113](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16113)

Encodes the specified Header message. Does not implicitly [verify](Header.md#verify) messages.

#### Parameters

##### message

[`IHeader`](../interfaces/IHeader.md)

Header message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16121](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16121)

Encodes the specified Header message, length delimited. Does not implicitly [verify](Header.md#verify) messages.

#### Parameters

##### message

[`IHeader`](../interfaces/IHeader.md)

Header message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:16154](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16154)

Creates a Header message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Header`](Header.md)

Header

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16162](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16162)

Creates a plain object from a Header message. Also converts values to other types if specified.

#### Parameters

##### message

[`Header`](Header.md)

Header

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16147](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16147)

Verifies a Header message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
