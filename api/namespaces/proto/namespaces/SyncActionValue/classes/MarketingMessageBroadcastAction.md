# Class: MarketingMessageBroadcastAction

Defined in: [WAProto/index.d.ts:32073](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32073)

Represents a MarketingMessageBroadcastAction.

## Implements

- [`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

## Constructors

### new MarketingMessageBroadcastAction()

> **new MarketingMessageBroadcastAction**(`properties`?): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:32079](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32079)

Constructs a new MarketingMessageBroadcastAction.

#### Parameters

##### properties?

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

Properties to set

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

## Properties

### repliedCount

> **repliedCount**: `number`

Defined in: [WAProto/index.d.ts:32082](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32082)

MarketingMessageBroadcastAction repliedCount.

#### Implementation of

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md).[`repliedCount`](../interfaces/IMarketingMessageBroadcastAction.md#repliedcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32152](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32152)

Converts this MarketingMessageBroadcastAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:32089](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32089)

Creates a new MarketingMessageBroadcastAction instance using the specified properties.

#### Parameters

##### properties?

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

Properties to set

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

MarketingMessageBroadcastAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:32115](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32115)

Decodes a MarketingMessageBroadcastAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

MarketingMessageBroadcastAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:32124](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32124)

Decodes a MarketingMessageBroadcastAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

MarketingMessageBroadcastAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32097](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32097)

Encodes the specified MarketingMessageBroadcastAction message. Does not implicitly [verify](MarketingMessageBroadcastAction.md#verify) messages.

#### Parameters

##### message

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

MarketingMessageBroadcastAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32105](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32105)

Encodes the specified MarketingMessageBroadcastAction message, length delimited. Does not implicitly [verify](MarketingMessageBroadcastAction.md#verify) messages.

#### Parameters

##### message

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

MarketingMessageBroadcastAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:32138](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32138)

Creates a MarketingMessageBroadcastAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

MarketingMessageBroadcastAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32146](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32146)

Creates a plain object from a MarketingMessageBroadcastAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

MarketingMessageBroadcastAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32131](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32131)

Verifies a MarketingMessageBroadcastAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
