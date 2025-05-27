# Class: ProductListInfo

Defined in: [WAProto/index.d.ts:17397](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17397)

Represents a ProductListInfo.

## Implements

- [`IProductListInfo`](../interfaces/IProductListInfo.md)

## Constructors

### new ProductListInfo()

> **new ProductListInfo**(`properties`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:17403](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17403)

Constructs a new ProductListInfo.

#### Parameters

##### properties?

[`IProductListInfo`](../interfaces/IProductListInfo.md)

Properties to set

#### Returns

[`ProductListInfo`](ProductListInfo.md)

## Properties

### businessOwnerJid

> **businessOwnerJid**: `string`

Defined in: [WAProto/index.d.ts:17412](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17412)

ProductListInfo businessOwnerJid.

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`businessOwnerJid`](../interfaces/IProductListInfo.md#businessownerjid)

***

### headerImage?

> `optional` **headerImage**: `null` \| [`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:17409](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17409)

ProductListInfo headerImage.

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`headerImage`](../interfaces/IProductListInfo.md#headerimage)

***

### productSections

> **productSections**: [`IProductSection`](../interfaces/IProductSection.md)[]

Defined in: [WAProto/index.d.ts:17406](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17406)

ProductListInfo productSections.

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`productSections`](../interfaces/IProductListInfo.md#productsections)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17482](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17482)

Converts this ProductListInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:17419](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17419)

Creates a new ProductListInfo instance using the specified properties.

#### Parameters

##### properties?

[`IProductListInfo`](../interfaces/IProductListInfo.md)

Properties to set

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:17445](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17445)

Decodes a ProductListInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:17454](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17454)

Decodes a ProductListInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17427](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17427)

Encodes the specified ProductListInfo message. Does not implicitly [verify](ProductListInfo.md#verify) messages.

#### Parameters

##### message

[`IProductListInfo`](../interfaces/IProductListInfo.md)

ProductListInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17435](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17435)

Encodes the specified ProductListInfo message, length delimited. Does not implicitly [verify](ProductListInfo.md#verify) messages.

#### Parameters

##### message

[`IProductListInfo`](../interfaces/IProductListInfo.md)

ProductListInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:17468](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17468)

Creates a ProductListInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17476](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17476)

Creates a plain object from a ProductListInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductListInfo`](ProductListInfo.md)

ProductListInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17461](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17461)

Verifies a ProductListInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
