# Class: InvoiceMessage

Defined in: [WAProto/index.d.ts:16836](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16836)

Represents an InvoiceMessage.

## Implements

- [`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

## Constructors

### new InvoiceMessage()

> **new InvoiceMessage**(`properties`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:16842](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16842)

Constructs a new InvoiceMessage.

#### Parameters

##### properties?

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

Properties to set

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

## Properties

### attachmentDirectPath

> **attachmentDirectPath**: `string`

Defined in: [WAProto/index.d.ts:16869](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16869)

InvoiceMessage attachmentDirectPath.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentDirectPath`](../interfaces/IInvoiceMessage.md#attachmentdirectpath)

***

### attachmentFileEncSha256

> **attachmentFileEncSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:16866](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16866)

InvoiceMessage attachmentFileEncSha256.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentFileEncSha256`](../interfaces/IInvoiceMessage.md#attachmentfileencsha256)

***

### attachmentFileSha256

> **attachmentFileSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:16863](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16863)

InvoiceMessage attachmentFileSha256.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentFileSha256`](../interfaces/IInvoiceMessage.md#attachmentfilesha256)

***

### attachmentJpegThumbnail

> **attachmentJpegThumbnail**: `Uint8Array`

Defined in: [WAProto/index.d.ts:16872](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16872)

InvoiceMessage attachmentJpegThumbnail.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentJpegThumbnail`](../interfaces/IInvoiceMessage.md#attachmentjpegthumbnail)

***

### attachmentMediaKey

> **attachmentMediaKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:16857](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16857)

InvoiceMessage attachmentMediaKey.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMediaKey`](../interfaces/IInvoiceMessage.md#attachmentmediakey)

***

### attachmentMediaKeyTimestamp

> **attachmentMediaKeyTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:16860](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16860)

InvoiceMessage attachmentMediaKeyTimestamp.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMediaKeyTimestamp`](../interfaces/IInvoiceMessage.md#attachmentmediakeytimestamp)

***

### attachmentMimetype

> **attachmentMimetype**: `string`

Defined in: [WAProto/index.d.ts:16854](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16854)

InvoiceMessage attachmentMimetype.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMimetype`](../interfaces/IInvoiceMessage.md#attachmentmimetype)

***

### attachmentType

> **attachmentType**: [`AttachmentType`](../namespaces/InvoiceMessage/enumerations/AttachmentType.md)

Defined in: [WAProto/index.d.ts:16851](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16851)

InvoiceMessage attachmentType.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentType`](../interfaces/IInvoiceMessage.md#attachmenttype)

***

### note

> **note**: `string`

Defined in: [WAProto/index.d.ts:16845](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16845)

InvoiceMessage note.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`note`](../interfaces/IInvoiceMessage.md#note)

***

### token

> **token**: `string`

Defined in: [WAProto/index.d.ts:16848](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16848)

InvoiceMessage token.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`token`](../interfaces/IInvoiceMessage.md#token)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16942](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16942)

Converts this InvoiceMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:16879](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16879)

Creates a new InvoiceMessage instance using the specified properties.

#### Parameters

##### properties?

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

Properties to set

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:16905](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16905)

Decodes an InvoiceMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:16914](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16914)

Decodes an InvoiceMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16887](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16887)

Encodes the specified InvoiceMessage message. Does not implicitly [verify](InvoiceMessage.md#verify) messages.

#### Parameters

##### message

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

InvoiceMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16895](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16895)

Encodes the specified InvoiceMessage message, length delimited. Does not implicitly [verify](InvoiceMessage.md#verify) messages.

#### Parameters

##### message

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

InvoiceMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:16928](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16928)

Creates an InvoiceMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16936](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16936)

Creates a plain object from an InvoiceMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16921](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16921)

Verifies an InvoiceMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
