# Class: DeclinePaymentRequestMessage

Defined in: [WAProto/index.d.ts:12628](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12628)

Represents a DeclinePaymentRequestMessage.

## Implements

- [`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

## Constructors

### new DeclinePaymentRequestMessage()

> **new DeclinePaymentRequestMessage**(`properties`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12634](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12634)

Constructs a new DeclinePaymentRequestMessage.

#### Parameters

##### properties?

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

Properties to set

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:12637](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12637)

DeclinePaymentRequestMessage key.

#### Implementation of

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md).[`key`](../interfaces/IDeclinePaymentRequestMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12707](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12707)

Converts this DeclinePaymentRequestMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12644](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12644)

Creates a new DeclinePaymentRequestMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

Properties to set

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12670](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12670)

Decodes a DeclinePaymentRequestMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12679](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12679)

Decodes a DeclinePaymentRequestMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12652](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12652)

Encodes the specified DeclinePaymentRequestMessage message. Does not implicitly [verify](DeclinePaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12660](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12660)

Encodes the specified DeclinePaymentRequestMessage message, length delimited. Does not implicitly [verify](DeclinePaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12693](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12693)

Creates a DeclinePaymentRequestMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12701](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12701)

Creates a plain object from a DeclinePaymentRequestMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12686](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12686)

Verifies a DeclinePaymentRequestMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
