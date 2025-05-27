# Class: PaymentInfoAction

Defined in: [WAProto/index.d.ts:32355](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32355)

Represents a PaymentInfoAction.

## Implements

- [`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

## Constructors

### new PaymentInfoAction()

> **new PaymentInfoAction**(`properties`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:32361](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32361)

Constructs a new PaymentInfoAction.

#### Parameters

##### properties?

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

Properties to set

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

## Properties

### cpi

> **cpi**: `string`

Defined in: [WAProto/index.d.ts:32364](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32364)

PaymentInfoAction cpi.

#### Implementation of

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md).[`cpi`](../interfaces/IPaymentInfoAction.md#cpi)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32434](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32434)

Converts this PaymentInfoAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:32371](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32371)

Creates a new PaymentInfoAction instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

Properties to set

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:32397](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32397)

Decodes a PaymentInfoAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:32406](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32406)

Decodes a PaymentInfoAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32379](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32379)

Encodes the specified PaymentInfoAction message. Does not implicitly [verify](PaymentInfoAction.md#verify) messages.

#### Parameters

##### message

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

PaymentInfoAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32387](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32387)

Encodes the specified PaymentInfoAction message, length delimited. Does not implicitly [verify](PaymentInfoAction.md#verify) messages.

#### Parameters

##### message

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

PaymentInfoAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:32420](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32420)

Creates a PaymentInfoAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32428](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32428)

Creates a plain object from a PaymentInfoAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32413](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32413)

Verifies a PaymentInfoAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
