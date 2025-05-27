# Class: RequestPaymentMessage

Defined in: [WAProto/index.d.ts:21431](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21431)

Represents a RequestPaymentMessage.

## Implements

- [`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

## Constructors

### new RequestPaymentMessage()

> **new RequestPaymentMessage**(`properties`?): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21437](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21437)

Constructs a new RequestPaymentMessage.

#### Parameters

##### properties?

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

Properties to set

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

## Properties

### amount?

> `optional` **amount**: `null` \| [`IMoney`](../../../interfaces/IMoney.md)

Defined in: [WAProto/index.d.ts:21455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21455)

RequestPaymentMessage amount.

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`amount`](../interfaces/IRequestPaymentMessage.md#amount)

***

### amount1000

> **amount1000**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:21446](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21446)

RequestPaymentMessage amount1000.

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`amount1000`](../interfaces/IRequestPaymentMessage.md#amount1000)

***

### background?

> `optional` **background**: `null` \| [`IPaymentBackground`](../../../interfaces/IPaymentBackground.md)

Defined in: [WAProto/index.d.ts:21458](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21458)

RequestPaymentMessage background.

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`background`](../interfaces/IRequestPaymentMessage.md#background)

***

### currencyCodeIso4217

> **currencyCodeIso4217**: `string`

Defined in: [WAProto/index.d.ts:21443](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21443)

RequestPaymentMessage currencyCodeIso4217.

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`currencyCodeIso4217`](../interfaces/IRequestPaymentMessage.md#currencycodeiso4217)

***

### expiryTimestamp

> **expiryTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:21452](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21452)

RequestPaymentMessage expiryTimestamp.

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`expiryTimestamp`](../interfaces/IRequestPaymentMessage.md#expirytimestamp)

***

### noteMessage?

> `optional` **noteMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:21440](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21440)

RequestPaymentMessage noteMessage.

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`noteMessage`](../interfaces/IRequestPaymentMessage.md#notemessage)

***

### requestFrom

> **requestFrom**: `string`

Defined in: [WAProto/index.d.ts:21449](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21449)

RequestPaymentMessage requestFrom.

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`requestFrom`](../interfaces/IRequestPaymentMessage.md#requestfrom)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21528](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21528)

Converts this RequestPaymentMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21465](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21465)

Creates a new RequestPaymentMessage instance using the specified properties.

#### Parameters

##### properties?

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

Properties to set

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

RequestPaymentMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21491](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21491)

Decodes a RequestPaymentMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

RequestPaymentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21500](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21500)

Decodes a RequestPaymentMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

RequestPaymentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21473](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21473)

Encodes the specified RequestPaymentMessage message. Does not implicitly [verify](RequestPaymentMessage.md#verify) messages.

#### Parameters

##### message

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

RequestPaymentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21481](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21481)

Encodes the specified RequestPaymentMessage message, length delimited. Does not implicitly [verify](RequestPaymentMessage.md#verify) messages.

#### Parameters

##### message

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

RequestPaymentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21514](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21514)

Creates a RequestPaymentMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

RequestPaymentMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21522](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21522)

Creates a plain object from a RequestPaymentMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`RequestPaymentMessage`](RequestPaymentMessage.md)

RequestPaymentMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21507](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21507)

Verifies a RequestPaymentMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
