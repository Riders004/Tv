# Class: ProductSection

Defined in: [WAProto/index.d.ts:17496](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17496)

Represents a ProductSection.

## Implements

- [`IProductSection`](../interfaces/IProductSection.md)

## Constructors

### new ProductSection()

> **new ProductSection**(`properties`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:17502](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17502)

Constructs a new ProductSection.

#### Parameters

##### properties?

[`IProductSection`](../interfaces/IProductSection.md)

Properties to set

#### Returns

[`ProductSection`](ProductSection.md)

## Properties

### products

> **products**: [`IProduct`](../interfaces/IProduct.md)[]

Defined in: [WAProto/index.d.ts:17508](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17508)

ProductSection products.

#### Implementation of

[`IProductSection`](../interfaces/IProductSection.md).[`products`](../interfaces/IProductSection.md#products)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:17505](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17505)

ProductSection title.

#### Implementation of

[`IProductSection`](../interfaces/IProductSection.md).[`title`](../interfaces/IProductSection.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17578)

Converts this ProductSection to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:17515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17515)

Creates a new ProductSection instance using the specified properties.

#### Parameters

##### properties?

[`IProductSection`](../interfaces/IProductSection.md)

Properties to set

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:17541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17541)

Decodes a ProductSection message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:17550](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17550)

Decodes a ProductSection message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17523](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17523)

Encodes the specified ProductSection message. Does not implicitly [verify](ProductSection.md#verify) messages.

#### Parameters

##### message

[`IProductSection`](../interfaces/IProductSection.md)

ProductSection message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17531](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17531)

Encodes the specified ProductSection message, length delimited. Does not implicitly [verify](ProductSection.md#verify) messages.

#### Parameters

##### message

[`IProductSection`](../interfaces/IProductSection.md)

ProductSection message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:17564](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17564)

Creates a ProductSection message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductSection`](ProductSection.md)

ProductSection

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17572](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17572)

Creates a plain object from a ProductSection message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductSection`](ProductSection.md)

ProductSection

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17557](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17557)

Verifies a ProductSection message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
