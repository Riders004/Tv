# Class: SendPaymentMessage

Defined in: [WAProto/index.d.ts:21951](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21951)

Represents a SendPaymentMessage.

## Implements

- [`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

## Constructors

### new SendPaymentMessage()

> **new SendPaymentMessage**(`properties`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21957](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21957)

Constructs a new SendPaymentMessage.

#### Parameters

##### properties?

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

Properties to set

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

## Properties

### background?

> `optional` **background**: `null` \| [`IPaymentBackground`](../../../interfaces/IPaymentBackground.md)

Defined in: [WAProto/index.d.ts:21966](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21966)

SendPaymentMessage background.

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`background`](../interfaces/ISendPaymentMessage.md#background)

***

### noteMessage?

> `optional` **noteMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:21960](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21960)

SendPaymentMessage noteMessage.

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`noteMessage`](../interfaces/ISendPaymentMessage.md#notemessage)

***

### requestMessageKey?

> `optional` **requestMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:21963](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21963)

SendPaymentMessage requestMessageKey.

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`requestMessageKey`](../interfaces/ISendPaymentMessage.md#requestmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22036](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22036)

Converts this SendPaymentMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21973](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21973)

Creates a new SendPaymentMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

Properties to set

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:21999](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21999)

Decodes a SendPaymentMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:22008](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22008)

Decodes a SendPaymentMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21981](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21981)

Encodes the specified SendPaymentMessage message. Does not implicitly [verify](SendPaymentMessage.md#verify) messages.

#### Parameters

##### message

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

SendPaymentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21989](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21989)

Encodes the specified SendPaymentMessage message, length delimited. Does not implicitly [verify](SendPaymentMessage.md#verify) messages.

#### Parameters

##### message

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

SendPaymentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:22022](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22022)

Creates a SendPaymentMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:22030](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22030)

Creates a plain object from a SendPaymentMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22015](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22015)

Verifies a SendPaymentMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
