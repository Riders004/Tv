# Class: PnForLidChatAction

Defined in: [WAProto/index.d.ts:32535](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32535)

Represents a PnForLidChatAction.

## Implements

- [`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

## Constructors

### new PnForLidChatAction()

> **new PnForLidChatAction**(`properties`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:32541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32541)

Constructs a new PnForLidChatAction.

#### Parameters

##### properties?

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

Properties to set

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

## Properties

### pnJid

> **pnJid**: `string`

Defined in: [WAProto/index.d.ts:32544](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32544)

PnForLidChatAction pnJid.

#### Implementation of

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md).[`pnJid`](../interfaces/IPnForLidChatAction.md#pnjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32614](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32614)

Converts this PnForLidChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:32551](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32551)

Creates a new PnForLidChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

Properties to set

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:32577](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32577)

Decodes a PnForLidChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:32586](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32586)

Decodes a PnForLidChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32559](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32559)

Encodes the specified PnForLidChatAction message. Does not implicitly [verify](PnForLidChatAction.md#verify) messages.

#### Parameters

##### message

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

PnForLidChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32567)

Encodes the specified PnForLidChatAction message, length delimited. Does not implicitly [verify](PnForLidChatAction.md#verify) messages.

#### Parameters

##### message

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

PnForLidChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:32600](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32600)

Creates a PnForLidChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32608](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32608)

Creates a plain object from a PnForLidChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32593](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32593)

Verifies a PnForLidChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
