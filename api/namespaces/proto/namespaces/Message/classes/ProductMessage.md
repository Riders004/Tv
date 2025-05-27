# Class: ProductMessage

Defined in: [WAProto/index.d.ts:20730](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20730)

Represents a ProductMessage.

## Implements

- [`IProductMessage`](../interfaces/IProductMessage.md)

## Constructors

### new ProductMessage()

> **new ProductMessage**(`properties`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:20736](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20736)

Constructs a new ProductMessage.

#### Parameters

##### properties?

[`IProductMessage`](../interfaces/IProductMessage.md)

Properties to set

#### Returns

[`ProductMessage`](ProductMessage.md)

## Properties

### body

> **body**: `string`

Defined in: [WAProto/index.d.ts:20748](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20748)

ProductMessage body.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`body`](../interfaces/IProductMessage.md#body)

***

### businessOwnerJid

> **businessOwnerJid**: `string`

Defined in: [WAProto/index.d.ts:20742](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20742)

ProductMessage businessOwnerJid.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`businessOwnerJid`](../interfaces/IProductMessage.md#businessownerjid)

***

### catalog?

> `optional` **catalog**: `null` \| [`ICatalogSnapshot`](../namespaces/ProductMessage/interfaces/ICatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:20745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20745)

ProductMessage catalog.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`catalog`](../interfaces/IProductMessage.md#catalog)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:20754](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20754)

ProductMessage contextInfo.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`contextInfo`](../interfaces/IProductMessage.md#contextinfo)

***

### footer

> **footer**: `string`

Defined in: [WAProto/index.d.ts:20751](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20751)

ProductMessage footer.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`footer`](../interfaces/IProductMessage.md#footer)

***

### product?

> `optional` **product**: `null` \| [`IProductSnapshot`](../namespaces/ProductMessage/interfaces/IProductSnapshot.md)

Defined in: [WAProto/index.d.ts:20739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20739)

ProductMessage product.

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`product`](../interfaces/IProductMessage.md#product)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20824](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20824)

Converts this ProductMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:20761](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20761)

Creates a new ProductMessage instance using the specified properties.

#### Parameters

##### properties?

[`IProductMessage`](../interfaces/IProductMessage.md)

Properties to set

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:20787](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20787)

Decodes a ProductMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:20796](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20796)

Decodes a ProductMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20769](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20769)

Encodes the specified ProductMessage message. Does not implicitly [verify](ProductMessage.md#verify) messages.

#### Parameters

##### message

[`IProductMessage`](../interfaces/IProductMessage.md)

ProductMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20777](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20777)

Encodes the specified ProductMessage message, length delimited. Does not implicitly [verify](ProductMessage.md#verify) messages.

#### Parameters

##### message

[`IProductMessage`](../interfaces/IProductMessage.md)

ProductMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:20810](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20810)

Creates a ProductMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductMessage`](ProductMessage.md)

ProductMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20818](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20818)

Creates a plain object from a ProductMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductMessage`](ProductMessage.md)

ProductMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20803](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20803)

Verifies a ProductMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
