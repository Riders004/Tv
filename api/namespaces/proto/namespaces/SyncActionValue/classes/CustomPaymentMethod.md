# Class: CustomPaymentMethod

Defined in: [WAProto/index.d.ts:30712](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30712)

Represents a CustomPaymentMethod.

## Implements

- [`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

## Constructors

### new CustomPaymentMethod()

> **new CustomPaymentMethod**(`properties`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:30718](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30718)

Constructs a new CustomPaymentMethod.

#### Parameters

##### properties?

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

Properties to set

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

## Properties

### country

> **country**: `string`

Defined in: [WAProto/index.d.ts:30724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30724)

CustomPaymentMethod country.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`country`](../interfaces/ICustomPaymentMethod.md#country)

***

### credentialId

> **credentialId**: `string`

Defined in: [WAProto/index.d.ts:30721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30721)

CustomPaymentMethod credentialId.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`credentialId`](../interfaces/ICustomPaymentMethod.md#credentialid)

***

### metadata

> **metadata**: [`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)[]

Defined in: [WAProto/index.d.ts:30730](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30730)

CustomPaymentMethod metadata.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`metadata`](../interfaces/ICustomPaymentMethod.md#metadata)

***

### type

> **type**: `string`

Defined in: [WAProto/index.d.ts:30727](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30727)

CustomPaymentMethod type.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`type`](../interfaces/ICustomPaymentMethod.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30800](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30800)

Converts this CustomPaymentMethod to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:30737](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30737)

Creates a new CustomPaymentMethod instance using the specified properties.

#### Parameters

##### properties?

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

Properties to set

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:30763](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30763)

Decodes a CustomPaymentMethod message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:30772](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30772)

Decodes a CustomPaymentMethod message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30745)

Encodes the specified CustomPaymentMethod message. Does not implicitly [verify](CustomPaymentMethod.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

CustomPaymentMethod message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30753](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30753)

Encodes the specified CustomPaymentMethod message, length delimited. Does not implicitly [verify](CustomPaymentMethod.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

CustomPaymentMethod message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:30786](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30786)

Creates a CustomPaymentMethod message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30794)

Creates a plain object from a CustomPaymentMethod message. Also converts values to other types if specified.

#### Parameters

##### message

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30779](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30779)

Verifies a CustomPaymentMethod message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
