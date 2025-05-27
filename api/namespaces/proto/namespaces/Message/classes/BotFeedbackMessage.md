# Class: BotFeedbackMessage

Defined in: [WAProto/index.d.ts:11080](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11080)

Represents a BotFeedbackMessage.

## Implements

- [`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

## Constructors

### new BotFeedbackMessage()

> **new BotFeedbackMessage**(`properties`?): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:11086](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11086)

Constructs a new BotFeedbackMessage.

#### Parameters

##### properties?

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

Properties to set

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

## Properties

### kind

> **kind**: [`BotFeedbackKind`](../namespaces/BotFeedbackMessage/enumerations/BotFeedbackKind.md)

Defined in: [WAProto/index.d.ts:11092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11092)

BotFeedbackMessage kind.

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`kind`](../interfaces/IBotFeedbackMessage.md#kind)

***

### kindNegative

> **kindNegative**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:11098](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11098)

BotFeedbackMessage kindNegative.

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`kindNegative`](../interfaces/IBotFeedbackMessage.md#kindnegative)

***

### kindPositive

> **kindPositive**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:11101](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11101)

BotFeedbackMessage kindPositive.

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`kindPositive`](../interfaces/IBotFeedbackMessage.md#kindpositive)

***

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:11089](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11089)

BotFeedbackMessage messageKey.

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`messageKey`](../interfaces/IBotFeedbackMessage.md#messagekey)

***

### text

> **text**: `string`

Defined in: [WAProto/index.d.ts:11095](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11095)

BotFeedbackMessage text.

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`text`](../interfaces/IBotFeedbackMessage.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11171](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11171)

Converts this BotFeedbackMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:11108](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11108)

Creates a new BotFeedbackMessage instance using the specified properties.

#### Parameters

##### properties?

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

Properties to set

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

BotFeedbackMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:11134](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11134)

Decodes a BotFeedbackMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

BotFeedbackMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:11143](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11143)

Decodes a BotFeedbackMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

BotFeedbackMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11116](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11116)

Encodes the specified BotFeedbackMessage message. Does not implicitly [verify](BotFeedbackMessage.md#verify) messages.

#### Parameters

##### message

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

BotFeedbackMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11124](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11124)

Encodes the specified BotFeedbackMessage message, length delimited. Does not implicitly [verify](BotFeedbackMessage.md#verify) messages.

#### Parameters

##### message

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

BotFeedbackMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:11157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11157)

Creates a BotFeedbackMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

BotFeedbackMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11165](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11165)

Creates a plain object from a BotFeedbackMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotFeedbackMessage`](BotFeedbackMessage.md)

BotFeedbackMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11150](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11150)

Verifies a BotFeedbackMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
