# Class: SenderKeyDistributionMessage

Defined in: [WAProto/index.d.ts:27449](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27449)

Represents a SenderKeyDistributionMessage.

## Implements

- [`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

## Constructors

### new SenderKeyDistributionMessage()

> **new SenderKeyDistributionMessage**(`properties`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:27455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27455)

Constructs a new SenderKeyDistributionMessage.

#### Parameters

##### properties?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

Properties to set

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

## Properties

### chainKey

> **chainKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:27464](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27464)

SenderKeyDistributionMessage chainKey.

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`chainKey`](../interfaces/ISenderKeyDistributionMessage.md#chainkey)

***

### id

> **id**: `number`

Defined in: [WAProto/index.d.ts:27458](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27458)

SenderKeyDistributionMessage id.

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`id`](../interfaces/ISenderKeyDistributionMessage.md#id)

***

### iteration

> **iteration**: `number`

Defined in: [WAProto/index.d.ts:27461](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27461)

SenderKeyDistributionMessage iteration.

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`iteration`](../interfaces/ISenderKeyDistributionMessage.md#iteration)

***

### signingKey

> **signingKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:27467](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27467)

SenderKeyDistributionMessage signingKey.

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`signingKey`](../interfaces/ISenderKeyDistributionMessage.md#signingkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27537](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27537)

Converts this SenderKeyDistributionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:27474](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27474)

Creates a new SenderKeyDistributionMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

Properties to set

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:27500](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27500)

Decodes a SenderKeyDistributionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:27509](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27509)

Decodes a SenderKeyDistributionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27482](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27482)

Encodes the specified SenderKeyDistributionMessage message. Does not implicitly [verify](SenderKeyDistributionMessage.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

SenderKeyDistributionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27490](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27490)

Encodes the specified SenderKeyDistributionMessage message, length delimited. Does not implicitly [verify](SenderKeyDistributionMessage.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

SenderKeyDistributionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:27523](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27523)

Creates a SenderKeyDistributionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27531](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27531)

Creates a plain object from a SenderKeyDistributionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27516](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27516)

Verifies a SenderKeyDistributionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
