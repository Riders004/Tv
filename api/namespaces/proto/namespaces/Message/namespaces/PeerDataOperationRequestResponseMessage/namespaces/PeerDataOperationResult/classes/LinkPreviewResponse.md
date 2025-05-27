# Class: LinkPreviewResponse

Defined in: [WAProto/index.d.ts:19579](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19579)

Represents a LinkPreviewResponse.

## Implements

- [`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

## Constructors

### new LinkPreviewResponse()

> **new LinkPreviewResponse**(`properties`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:19585](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19585)

Constructs a new LinkPreviewResponse.

#### Parameters

##### properties?

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

Properties to set

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

## Properties

### canonicalUrl

> **canonicalUrl**: `string`

Defined in: [WAProto/index.d.ts:19600](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19600)

LinkPreviewResponse canonicalUrl.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`canonicalUrl`](../interfaces/ILinkPreviewResponse.md#canonicalurl)

***

### description

> **description**: `string`

Defined in: [WAProto/index.d.ts:19594](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19594)

LinkPreviewResponse description.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`description`](../interfaces/ILinkPreviewResponse.md#description)

***

### hqThumbnail?

> `optional` **hqThumbnail**: `null` \| [`ILinkPreviewHighQualityThumbnail`](../namespaces/LinkPreviewResponse/interfaces/ILinkPreviewHighQualityThumbnail.md)

Defined in: [WAProto/index.d.ts:19609](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19609)

LinkPreviewResponse hqThumbnail.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`hqThumbnail`](../interfaces/ILinkPreviewResponse.md#hqthumbnail)

***

### matchText

> **matchText**: `string`

Defined in: [WAProto/index.d.ts:19603](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19603)

LinkPreviewResponse matchText.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`matchText`](../interfaces/ILinkPreviewResponse.md#matchtext)

***

### previewType

> **previewType**: `string`

Defined in: [WAProto/index.d.ts:19606](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19606)

LinkPreviewResponse previewType.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`previewType`](../interfaces/ILinkPreviewResponse.md#previewtype)

***

### thumbData

> **thumbData**: `Uint8Array`

Defined in: [WAProto/index.d.ts:19597](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19597)

LinkPreviewResponse thumbData.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`thumbData`](../interfaces/ILinkPreviewResponse.md#thumbdata)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:19591](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19591)

LinkPreviewResponse title.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`title`](../interfaces/ILinkPreviewResponse.md#title)

***

### url

> **url**: `string`

Defined in: [WAProto/index.d.ts:19588](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19588)

LinkPreviewResponse url.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`url`](../interfaces/ILinkPreviewResponse.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19679](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19679)

Converts this LinkPreviewResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:19616](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19616)

Creates a new LinkPreviewResponse instance using the specified properties.

#### Parameters

##### properties?

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

Properties to set

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:19642](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19642)

Decodes a LinkPreviewResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:19651](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19651)

Decodes a LinkPreviewResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19624](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19624)

Encodes the specified LinkPreviewResponse message. Does not implicitly [verify](LinkPreviewResponse.md#verify) messages.

#### Parameters

##### message

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

LinkPreviewResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19632](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19632)

Encodes the specified LinkPreviewResponse message, length delimited. Does not implicitly [verify](LinkPreviewResponse.md#verify) messages.

#### Parameters

##### message

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

LinkPreviewResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:19665](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19665)

Creates a LinkPreviewResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:19673](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19673)

Creates a plain object from a LinkPreviewResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19658](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19658)

Verifies a LinkPreviewResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
