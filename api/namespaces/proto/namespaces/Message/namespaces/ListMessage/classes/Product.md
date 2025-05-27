# Class: Product

Defined in: [WAProto/index.d.ts:17205](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17205)

Represents a Product.

## Implements

- [`IProduct`](../interfaces/IProduct.md)

## Constructors

### new Product()

> **new Product**(`properties`?): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:17211](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17211)

Constructs a new Product.

#### Parameters

##### properties?

[`IProduct`](../interfaces/IProduct.md)

Properties to set

#### Returns

[`Product`](Product.md)

## Properties

### productId

> **productId**: `string`

Defined in: [WAProto/index.d.ts:17214](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17214)

Product productId.

#### Implementation of

[`IProduct`](../interfaces/IProduct.md).[`productId`](../interfaces/IProduct.md#productid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17284](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17284)

Converts this Product to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:17221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17221)

Creates a new Product instance using the specified properties.

#### Parameters

##### properties?

[`IProduct`](../interfaces/IProduct.md)

Properties to set

#### Returns

[`Product`](Product.md)

Product instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:17247](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17247)

Decodes a Product message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Product`](Product.md)

Product

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:17256](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17256)

Decodes a Product message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Product`](Product.md)

Product

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17229](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17229)

Encodes the specified Product message. Does not implicitly [verify](Product.md#verify) messages.

#### Parameters

##### message

[`IProduct`](../interfaces/IProduct.md)

Product message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17237](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17237)

Encodes the specified Product message, length delimited. Does not implicitly [verify](Product.md#verify) messages.

#### Parameters

##### message

[`IProduct`](../interfaces/IProduct.md)

Product message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:17270](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17270)

Creates a Product message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Product`](Product.md)

Product

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17278](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17278)

Creates a plain object from a Product message. Also converts values to other types if specified.

#### Parameters

##### message

[`Product`](Product.md)

Product

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17263](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17263)

Verifies a Product message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
