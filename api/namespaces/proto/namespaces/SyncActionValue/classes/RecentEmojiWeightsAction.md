# Class: RecentEmojiWeightsAction

Defined in: [WAProto/index.d.ts:33099](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33099)

Represents a RecentEmojiWeightsAction.

## Implements

- [`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

## Constructors

### new RecentEmojiWeightsAction()

> **new RecentEmojiWeightsAction**(`properties`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:33105](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33105)

Constructs a new RecentEmojiWeightsAction.

#### Parameters

##### properties?

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

Properties to set

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

## Properties

### weights

> **weights**: [`IRecentEmojiWeight`](../../../interfaces/IRecentEmojiWeight.md)[]

Defined in: [WAProto/index.d.ts:33108](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33108)

RecentEmojiWeightsAction weights.

#### Implementation of

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md).[`weights`](../interfaces/IRecentEmojiWeightsAction.md#weights)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33178](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33178)

Converts this RecentEmojiWeightsAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:33115](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33115)

Creates a new RecentEmojiWeightsAction instance using the specified properties.

#### Parameters

##### properties?

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

Properties to set

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:33141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33141)

Decodes a RecentEmojiWeightsAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:33150](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33150)

Decodes a RecentEmojiWeightsAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33123](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33123)

Encodes the specified RecentEmojiWeightsAction message. Does not implicitly [verify](RecentEmojiWeightsAction.md#verify) messages.

#### Parameters

##### message

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

RecentEmojiWeightsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33131](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33131)

Encodes the specified RecentEmojiWeightsAction message, length delimited. Does not implicitly [verify](RecentEmojiWeightsAction.md#verify) messages.

#### Parameters

##### message

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

RecentEmojiWeightsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:33164](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33164)

Creates a RecentEmojiWeightsAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33172](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33172)

Creates a plain object from a RecentEmojiWeightsAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33157)

Verifies a RecentEmojiWeightsAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
