# Class: PaymentInviteMessage

Defined in: [WAProto/index.d.ts:18733](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18733)

Represents a PaymentInviteMessage.

## Implements

- [`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

## Constructors

### new PaymentInviteMessage()

> **new PaymentInviteMessage**(`properties`?): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:18739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18739)

Constructs a new PaymentInviteMessage.

#### Parameters

##### properties?

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

Properties to set

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

## Properties

### expiryTimestamp

> **expiryTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:18745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18745)

PaymentInviteMessage expiryTimestamp.

#### Implementation of

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md).[`expiryTimestamp`](../interfaces/IPaymentInviteMessage.md#expirytimestamp)

***

### serviceType

> **serviceType**: [`ServiceType`](../namespaces/PaymentInviteMessage/enumerations/ServiceType.md)

Defined in: [WAProto/index.d.ts:18742](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18742)

PaymentInviteMessage serviceType.

#### Implementation of

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md).[`serviceType`](../interfaces/IPaymentInviteMessage.md#servicetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:18815](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18815)

Converts this PaymentInviteMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:18752](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18752)

Creates a new PaymentInviteMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

Properties to set

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

PaymentInviteMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:18778](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18778)

Decodes a PaymentInviteMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

PaymentInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:18787](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18787)

Decodes a PaymentInviteMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

PaymentInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18760](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18760)

Encodes the specified PaymentInviteMessage message. Does not implicitly [verify](PaymentInviteMessage.md#verify) messages.

#### Parameters

##### message

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

PaymentInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18768](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18768)

Encodes the specified PaymentInviteMessage message, length delimited. Does not implicitly [verify](PaymentInviteMessage.md#verify) messages.

#### Parameters

##### message

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

PaymentInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:18801](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18801)

Creates a PaymentInviteMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

PaymentInviteMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:18809](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18809)

Creates a plain object from a PaymentInviteMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentInviteMessage`](PaymentInviteMessage.md)

PaymentInviteMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:18794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18794)

Verifies a PaymentInviteMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
