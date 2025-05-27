# Class: DraftMessage

Defined in: [WAProto/index.d.ts:2427](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2427)

Represents a DraftMessage.

## Implements

- [`IDraftMessage`](../interfaces/IDraftMessage.md)

## Constructors

### new DraftMessage()

> **new DraftMessage**(`properties`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2433](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2433)

Constructs a new DraftMessage.

#### Parameters

##### properties?

[`IDraftMessage`](../interfaces/IDraftMessage.md)

Properties to set

#### Returns

[`DraftMessage`](DraftMessage.md)

## Properties

### ctwaContext?

> `optional` **ctwaContext**: `null` \| [`ICtwaContextData`](../namespaces/DraftMessage/interfaces/ICtwaContextData.md)

Defined in: [WAProto/index.d.ts:2445](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2445)

DraftMessage ctwaContext.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`ctwaContext`](../interfaces/IDraftMessage.md#ctwacontext)

***

### ctwaContextLinkData?

> `optional` **ctwaContextLinkData**: `null` \| [`ICtwaContextLinkData`](../namespaces/DraftMessage/interfaces/ICtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2442](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2442)

DraftMessage ctwaContextLinkData.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`ctwaContextLinkData`](../interfaces/IDraftMessage.md#ctwacontextlinkdata)

***

### omittedUrl

> **omittedUrl**: `string`

Defined in: [WAProto/index.d.ts:2439](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2439)

DraftMessage omittedUrl.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`omittedUrl`](../interfaces/IDraftMessage.md#omittedurl)

***

### text

> **text**: `string`

Defined in: [WAProto/index.d.ts:2436](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2436)

DraftMessage text.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`text`](../interfaces/IDraftMessage.md#text)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:2448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2448)

DraftMessage timestamp.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`timestamp`](../interfaces/IDraftMessage.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2518)

Converts this DraftMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2455)

Creates a new DraftMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDraftMessage`](../interfaces/IDraftMessage.md)

Properties to set

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2481](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2481)

Decodes a DraftMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2490](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2490)

Decodes a DraftMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2463](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2463)

Encodes the specified DraftMessage message. Does not implicitly [verify](DraftMessage.md#verify) messages.

#### Parameters

##### message

[`IDraftMessage`](../interfaces/IDraftMessage.md)

DraftMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2471](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2471)

Encodes the specified DraftMessage message, length delimited. Does not implicitly [verify](DraftMessage.md#verify) messages.

#### Parameters

##### message

[`IDraftMessage`](../interfaces/IDraftMessage.md)

DraftMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2504](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2504)

Creates a DraftMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:2512](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2512)

Creates a plain object from a DraftMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DraftMessage`](DraftMessage.md)

DraftMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2497](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2497)

Verifies a DraftMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
