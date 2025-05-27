# Class: BotWelcomeRequestAction

Defined in: [WAProto/index.d.ts:30145](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30145)

Represents a BotWelcomeRequestAction.

## Implements

- [`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

## Constructors

### new BotWelcomeRequestAction()

> **new BotWelcomeRequestAction**(`properties`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:30151](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30151)

Constructs a new BotWelcomeRequestAction.

#### Parameters

##### properties?

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

Properties to set

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

## Properties

### isSent

> **isSent**: `boolean`

Defined in: [WAProto/index.d.ts:30154](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30154)

BotWelcomeRequestAction isSent.

#### Implementation of

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md).[`isSent`](../interfaces/IBotWelcomeRequestAction.md#issent)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30224](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30224)

Converts this BotWelcomeRequestAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:30161](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30161)

Creates a new BotWelcomeRequestAction instance using the specified properties.

#### Parameters

##### properties?

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

Properties to set

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:30187](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30187)

Decodes a BotWelcomeRequestAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:30196](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30196)

Decodes a BotWelcomeRequestAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30169](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30169)

Encodes the specified BotWelcomeRequestAction message. Does not implicitly [verify](BotWelcomeRequestAction.md#verify) messages.

#### Parameters

##### message

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

BotWelcomeRequestAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30177](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30177)

Encodes the specified BotWelcomeRequestAction message, length delimited. Does not implicitly [verify](BotWelcomeRequestAction.md#verify) messages.

#### Parameters

##### message

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

BotWelcomeRequestAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:30210](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30210)

Creates a BotWelcomeRequestAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30218](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30218)

Creates a plain object from a BotWelcomeRequestAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30203](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30203)

Verifies a BotWelcomeRequestAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
