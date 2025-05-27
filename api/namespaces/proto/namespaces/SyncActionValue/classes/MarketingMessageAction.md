# Class: MarketingMessageAction

Defined in: [WAProto/index.d.ts:31957](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31957)

Represents a MarketingMessageAction.

## Implements

- [`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

## Constructors

### new MarketingMessageAction()

> **new MarketingMessageAction**(`properties`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:31963](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31963)

Constructs a new MarketingMessageAction.

#### Parameters

##### properties?

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

Properties to set

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

## Properties

### createdAt

> **createdAt**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:31975](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31975)

MarketingMessageAction createdAt.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`createdAt`](../interfaces/IMarketingMessageAction.md#createdat)

***

### isDeleted

> **isDeleted**: `boolean`

Defined in: [WAProto/index.d.ts:31981](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31981)

MarketingMessageAction isDeleted.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`isDeleted`](../interfaces/IMarketingMessageAction.md#isdeleted)

***

### lastSentAt

> **lastSentAt**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:31978](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31978)

MarketingMessageAction lastSentAt.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`lastSentAt`](../interfaces/IMarketingMessageAction.md#lastsentat)

***

### mediaId

> **mediaId**: `string`

Defined in: [WAProto/index.d.ts:31984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31984)

MarketingMessageAction mediaId.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`mediaId`](../interfaces/IMarketingMessageAction.md#mediaid)

***

### message

> **message**: `string`

Defined in: [WAProto/index.d.ts:31969](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31969)

MarketingMessageAction message.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`message`](../interfaces/IMarketingMessageAction.md#message)

***

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:31966](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31966)

MarketingMessageAction name.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`name`](../interfaces/IMarketingMessageAction.md#name)

***

### type

> **type**: [`PERSONALIZED`](../namespaces/MarketingMessageAction/enumerations/MarketingMessagePrototypeType.md#personalized)

Defined in: [WAProto/index.d.ts:31972](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31972)

MarketingMessageAction type.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`type`](../interfaces/IMarketingMessageAction.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32054](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32054)

Converts this MarketingMessageAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:31991](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31991)

Creates a new MarketingMessageAction instance using the specified properties.

#### Parameters

##### properties?

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

Properties to set

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:32017](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32017)

Decodes a MarketingMessageAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:32026](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32026)

Decodes a MarketingMessageAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31999](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31999)

Encodes the specified MarketingMessageAction message. Does not implicitly [verify](MarketingMessageAction.md#verify) messages.

#### Parameters

##### message

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

MarketingMessageAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32007](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32007)

Encodes the specified MarketingMessageAction message, length delimited. Does not implicitly [verify](MarketingMessageAction.md#verify) messages.

#### Parameters

##### message

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

MarketingMessageAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:32040](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32040)

Creates a MarketingMessageAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32048](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32048)

Creates a plain object from a MarketingMessageAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32033](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32033)

Verifies a MarketingMessageAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
