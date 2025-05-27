# Class: ProductListHeaderImage

Defined in: [WAProto/index.d.ts:17298](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17298)

Represents a ProductListHeaderImage.

## Implements

- [`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

## Constructors

### new ProductListHeaderImage()

> **new ProductListHeaderImage**(`properties`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:17304](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17304)

Constructs a new ProductListHeaderImage.

#### Parameters

##### properties?

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

Properties to set

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

## Properties

### jpegThumbnail

> **jpegThumbnail**: `Uint8Array`

Defined in: [WAProto/index.d.ts:17310](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17310)

ProductListHeaderImage jpegThumbnail.

#### Implementation of

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md).[`jpegThumbnail`](../interfaces/IProductListHeaderImage.md#jpegthumbnail)

***

### productId

> **productId**: `string`

Defined in: [WAProto/index.d.ts:17307](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17307)

ProductListHeaderImage productId.

#### Implementation of

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md).[`productId`](../interfaces/IProductListHeaderImage.md#productid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17380](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17380)

Converts this ProductListHeaderImage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:17317](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17317)

Creates a new ProductListHeaderImage instance using the specified properties.

#### Parameters

##### properties?

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

Properties to set

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:17343](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17343)

Decodes a ProductListHeaderImage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:17352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17352)

Decodes a ProductListHeaderImage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17325](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17325)

Encodes the specified ProductListHeaderImage message. Does not implicitly [verify](ProductListHeaderImage.md#verify) messages.

#### Parameters

##### message

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

ProductListHeaderImage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17333](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17333)

Encodes the specified ProductListHeaderImage message, length delimited. Does not implicitly [verify](ProductListHeaderImage.md#verify) messages.

#### Parameters

##### message

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

ProductListHeaderImage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:17366](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17366)

Creates a ProductListHeaderImage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17374](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17374)

Creates a plain object from a ProductListHeaderImage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductListHeaderImage`](ProductListHeaderImage.md)

ProductListHeaderImage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17359)

Verifies a ProductListHeaderImage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
