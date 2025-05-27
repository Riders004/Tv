# Class: BotMetadata

Defined in: [WAProto/index.d.ts:1363](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1363)

Represents a BotMetadata.

## Implements

- [`IBotMetadata`](../interfaces/IBotMetadata.md)

## Constructors

### new BotMetadata()

> **new BotMetadata**(`properties`?): [`BotMetadata`](BotMetadata.md)

Defined in: [WAProto/index.d.ts:1369](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1369)

Constructs a new BotMetadata.

#### Parameters

##### properties?

[`IBotMetadata`](../interfaces/IBotMetadata.md)

Properties to set

#### Returns

[`BotMetadata`](BotMetadata.md)

## Properties

### avatarMetadata?

> `optional` **avatarMetadata**: `null` \| [`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:1372](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1372)

BotMetadata avatarMetadata.

#### Implementation of

[`IBotMetadata`](../interfaces/IBotMetadata.md).[`avatarMetadata`](../interfaces/IBotMetadata.md#avatarmetadata)

***

### invokerJid

> **invokerJid**: `string`

Defined in: [WAProto/index.d.ts:1384](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1384)

BotMetadata invokerJid.

#### Implementation of

[`IBotMetadata`](../interfaces/IBotMetadata.md).[`invokerJid`](../interfaces/IBotMetadata.md#invokerjid)

***

### personaId

> **personaId**: `string`

Defined in: [WAProto/index.d.ts:1375](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1375)

BotMetadata personaId.

#### Implementation of

[`IBotMetadata`](../interfaces/IBotMetadata.md).[`personaId`](../interfaces/IBotMetadata.md#personaid)

***

### pluginMetadata?

> `optional` **pluginMetadata**: `null` \| [`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md)

Defined in: [WAProto/index.d.ts:1378](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1378)

BotMetadata pluginMetadata.

#### Implementation of

[`IBotMetadata`](../interfaces/IBotMetadata.md).[`pluginMetadata`](../interfaces/IBotMetadata.md#pluginmetadata)

***

### suggestedPromptMetadata?

> `optional` **suggestedPromptMetadata**: `null` \| [`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md)

Defined in: [WAProto/index.d.ts:1381](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1381)

BotMetadata suggestedPromptMetadata.

#### Implementation of

[`IBotMetadata`](../interfaces/IBotMetadata.md).[`suggestedPromptMetadata`](../interfaces/IBotMetadata.md#suggestedpromptmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1454](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1454)

Converts this BotMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotMetadata`](BotMetadata.md)

Defined in: [WAProto/index.d.ts:1391](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1391)

Creates a new BotMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotMetadata`](../interfaces/IBotMetadata.md)

Properties to set

#### Returns

[`BotMetadata`](BotMetadata.md)

BotMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotMetadata`](BotMetadata.md)

Defined in: [WAProto/index.d.ts:1417](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1417)

Decodes a BotMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotMetadata`](BotMetadata.md)

BotMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotMetadata`](BotMetadata.md)

Defined in: [WAProto/index.d.ts:1426](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1426)

Decodes a BotMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotMetadata`](BotMetadata.md)

BotMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1399](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1399)

Encodes the specified BotMetadata message. Does not implicitly [verify](BotMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMetadata`](../interfaces/IBotMetadata.md)

BotMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1407](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1407)

Encodes the specified BotMetadata message, length delimited. Does not implicitly [verify](BotMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMetadata`](../interfaces/IBotMetadata.md)

BotMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotMetadata`](BotMetadata.md)

Defined in: [WAProto/index.d.ts:1440](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1440)

Creates a BotMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotMetadata`](BotMetadata.md)

BotMetadata

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:1448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1448)

Creates a plain object from a BotMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotMetadata`](BotMetadata.md)

BotMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1433](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1433)

Verifies a BotMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
