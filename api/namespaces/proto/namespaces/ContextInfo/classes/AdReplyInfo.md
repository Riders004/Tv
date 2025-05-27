# Class: AdReplyInfo

Defined in: [WAProto/index.d.ts:4444](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4444)

Represents an AdReplyInfo.

## Implements

- [`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

## Constructors

### new AdReplyInfo()

> **new AdReplyInfo**(`properties`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:4450](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4450)

Constructs a new AdReplyInfo.

#### Parameters

##### properties?

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

Properties to set

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

## Properties

### advertiserName

> **advertiserName**: `string`

Defined in: [WAProto/index.d.ts:4453](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4453)

AdReplyInfo advertiserName.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`advertiserName`](../interfaces/IAdReplyInfo.md#advertisername)

***

### caption

> **caption**: `string`

Defined in: [WAProto/index.d.ts:4462](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4462)

AdReplyInfo caption.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`caption`](../interfaces/IAdReplyInfo.md#caption)

***

### jpegThumbnail

> **jpegThumbnail**: `Uint8Array`

Defined in: [WAProto/index.d.ts:4459](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4459)

AdReplyInfo jpegThumbnail.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`jpegThumbnail`](../interfaces/IAdReplyInfo.md#jpegthumbnail)

***

### mediaType

> **mediaType**: [`MediaType`](../namespaces/AdReplyInfo/enumerations/MediaType.md)

Defined in: [WAProto/index.d.ts:4456](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4456)

AdReplyInfo mediaType.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`mediaType`](../interfaces/IAdReplyInfo.md#mediatype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4532](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4532)

Converts this AdReplyInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:4469](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4469)

Creates a new AdReplyInfo instance using the specified properties.

#### Parameters

##### properties?

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

Properties to set

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:4495](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4495)

Decodes an AdReplyInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:4504](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4504)

Decodes an AdReplyInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4477](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4477)

Encodes the specified AdReplyInfo message. Does not implicitly [verify](AdReplyInfo.md#verify) messages.

#### Parameters

##### message

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

AdReplyInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4485](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4485)

Encodes the specified AdReplyInfo message, length delimited. Does not implicitly [verify](AdReplyInfo.md#verify) messages.

#### Parameters

##### message

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

AdReplyInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:4518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4518)

Creates an AdReplyInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:4526](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4526)

Creates a plain object from an AdReplyInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4511](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4511)

Verifies an AdReplyInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
