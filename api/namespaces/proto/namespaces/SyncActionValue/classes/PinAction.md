# Class: PinAction

Defined in: [WAProto/index.d.ts:32445](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32445)

Represents a PinAction.

## Implements

- [`IPinAction`](../interfaces/IPinAction.md)

## Constructors

### new PinAction()

> **new PinAction**(`properties`?): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:32451](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32451)

Constructs a new PinAction.

#### Parameters

##### properties?

[`IPinAction`](../interfaces/IPinAction.md)

Properties to set

#### Returns

[`PinAction`](PinAction.md)

## Properties

### pinned

> **pinned**: `boolean`

Defined in: [WAProto/index.d.ts:32454](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32454)

PinAction pinned.

#### Implementation of

[`IPinAction`](../interfaces/IPinAction.md).[`pinned`](../interfaces/IPinAction.md#pinned)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32524](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32524)

Converts this PinAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:32461](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32461)

Creates a new PinAction instance using the specified properties.

#### Parameters

##### properties?

[`IPinAction`](../interfaces/IPinAction.md)

Properties to set

#### Returns

[`PinAction`](PinAction.md)

PinAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:32487](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32487)

Decodes a PinAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PinAction`](PinAction.md)

PinAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:32496](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32496)

Decodes a PinAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PinAction`](PinAction.md)

PinAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32469](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32469)

Encodes the specified PinAction message. Does not implicitly [verify](PinAction.md#verify) messages.

#### Parameters

##### message

[`IPinAction`](../interfaces/IPinAction.md)

PinAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32477](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32477)

Encodes the specified PinAction message, length delimited. Does not implicitly [verify](PinAction.md#verify) messages.

#### Parameters

##### message

[`IPinAction`](../interfaces/IPinAction.md)

PinAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:32510](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32510)

Creates a PinAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PinAction`](PinAction.md)

PinAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32518)

Creates a plain object from a PinAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PinAction`](PinAction.md)

PinAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32503](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32503)

Verifies a PinAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
