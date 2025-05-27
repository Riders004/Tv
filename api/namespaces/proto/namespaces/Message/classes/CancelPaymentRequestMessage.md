# Class: CancelPaymentRequestMessage

Defined in: [WAProto/index.d.ts:12142](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12142)

Represents a CancelPaymentRequestMessage.

## Implements

- [`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

## Constructors

### new CancelPaymentRequestMessage()

> **new CancelPaymentRequestMessage**(`properties`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12148](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12148)

Constructs a new CancelPaymentRequestMessage.

#### Parameters

##### properties?

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

Properties to set

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:12151](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12151)

CancelPaymentRequestMessage key.

#### Implementation of

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md).[`key`](../interfaces/ICancelPaymentRequestMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12221)

Converts this CancelPaymentRequestMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12158](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12158)

Creates a new CancelPaymentRequestMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

Properties to set

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12184](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12184)

Decodes a CancelPaymentRequestMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12193](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12193)

Decodes a CancelPaymentRequestMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12166](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12166)

Encodes the specified CancelPaymentRequestMessage message. Does not implicitly [verify](CancelPaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

CancelPaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12174](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12174)

Encodes the specified CancelPaymentRequestMessage message, length delimited. Does not implicitly [verify](CancelPaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

CancelPaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:12207](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12207)

Creates a CancelPaymentRequestMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12215](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12215)

Creates a plain object from a CancelPaymentRequestMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12200](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12200)

Verifies a CancelPaymentRequestMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
