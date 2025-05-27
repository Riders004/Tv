# Class: ProductSnapshot

Defined in: [WAProto/index.d.ts:20969](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20969)

Represents a ProductSnapshot.

## Implements

- [`IProductSnapshot`](../interfaces/IProductSnapshot.md)

## Constructors

### new ProductSnapshot()

> **new ProductSnapshot**(`properties`?): [`ProductSnapshot`](ProductSnapshot.md)

Defined in: [WAProto/index.d.ts:20975](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20975)

Constructs a new ProductSnapshot.

#### Parameters

##### properties?

[`IProductSnapshot`](../interfaces/IProductSnapshot.md)

Properties to set

#### Returns

[`ProductSnapshot`](ProductSnapshot.md)

## Properties

### currencyCode

> **currencyCode**: `string`

Defined in: [WAProto/index.d.ts:20990](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20990)

ProductSnapshot currencyCode.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`currencyCode`](../interfaces/IProductSnapshot.md#currencycode)

***

### description

> **description**: `string`

Defined in: [WAProto/index.d.ts:20987](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20987)

ProductSnapshot description.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`description`](../interfaces/IProductSnapshot.md#description)

***

### firstImageId

> **firstImageId**: `string`

Defined in: [WAProto/index.d.ts:21005](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21005)

ProductSnapshot firstImageId.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`firstImageId`](../interfaces/IProductSnapshot.md#firstimageid)

***

### priceAmount1000

> **priceAmount1000**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:20993](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20993)

ProductSnapshot priceAmount1000.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`priceAmount1000`](../interfaces/IProductSnapshot.md#priceamount1000)

***

### productId

> **productId**: `string`

Defined in: [WAProto/index.d.ts:20981](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20981)

ProductSnapshot productId.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`productId`](../interfaces/IProductSnapshot.md#productid)

***

### productImage?

> `optional` **productImage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:20978](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20978)

ProductSnapshot productImage.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`productImage`](../interfaces/IProductSnapshot.md#productimage)

***

### productImageCount

> **productImageCount**: `number`

Defined in: [WAProto/index.d.ts:21002](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21002)

ProductSnapshot productImageCount.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`productImageCount`](../interfaces/IProductSnapshot.md#productimagecount)

***

### retailerId

> **retailerId**: `string`

Defined in: [WAProto/index.d.ts:20996](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20996)

ProductSnapshot retailerId.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`retailerId`](../interfaces/IProductSnapshot.md#retailerid)

***

### salePriceAmount1000

> **salePriceAmount1000**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:21008](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21008)

ProductSnapshot salePriceAmount1000.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`salePriceAmount1000`](../interfaces/IProductSnapshot.md#salepriceamount1000)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:20984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20984)

ProductSnapshot title.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`title`](../interfaces/IProductSnapshot.md#title)

***

### url

> **url**: `string`

Defined in: [WAProto/index.d.ts:20999](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20999)

ProductSnapshot url.

#### Implementation of

[`IProductSnapshot`](../interfaces/IProductSnapshot.md).[`url`](../interfaces/IProductSnapshot.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21078](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21078)

Converts this ProductSnapshot to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProductSnapshot`](ProductSnapshot.md)

Defined in: [WAProto/index.d.ts:21015](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21015)

Creates a new ProductSnapshot instance using the specified properties.

#### Parameters

##### properties?

[`IProductSnapshot`](../interfaces/IProductSnapshot.md)

Properties to set

#### Returns

[`ProductSnapshot`](ProductSnapshot.md)

ProductSnapshot instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProductSnapshot`](ProductSnapshot.md)

Defined in: [WAProto/index.d.ts:21041](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21041)

Decodes a ProductSnapshot message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProductSnapshot`](ProductSnapshot.md)

ProductSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProductSnapshot`](ProductSnapshot.md)

Defined in: [WAProto/index.d.ts:21050](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21050)

Decodes a ProductSnapshot message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProductSnapshot`](ProductSnapshot.md)

ProductSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21023](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21023)

Encodes the specified ProductSnapshot message. Does not implicitly [verify](ProductSnapshot.md#verify) messages.

#### Parameters

##### message

[`IProductSnapshot`](../interfaces/IProductSnapshot.md)

ProductSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21031](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21031)

Encodes the specified ProductSnapshot message, length delimited. Does not implicitly [verify](ProductSnapshot.md#verify) messages.

#### Parameters

##### message

[`IProductSnapshot`](../interfaces/IProductSnapshot.md)

ProductSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProductSnapshot`](ProductSnapshot.md)

Defined in: [WAProto/index.d.ts:21064](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21064)

Creates a ProductSnapshot message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProductSnapshot`](ProductSnapshot.md)

ProductSnapshot

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21072](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21072)

Creates a plain object from a ProductSnapshot message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProductSnapshot`](ProductSnapshot.md)

ProductSnapshot

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21057](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21057)

Verifies a ProductSnapshot message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
