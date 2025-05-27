# Class: BotPluginMetadata

Defined in: [WAProto/index.d.ts:1486](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1486)

Represents a BotPluginMetadata.

## Implements

- [`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md)

## Constructors

### new BotPluginMetadata()

> **new BotPluginMetadata**(`properties`?): [`BotPluginMetadata`](BotPluginMetadata.md)

Defined in: [WAProto/index.d.ts:1492](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1492)

Constructs a new BotPluginMetadata.

#### Parameters

##### properties?

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md)

Properties to set

#### Returns

[`BotPluginMetadata`](BotPluginMetadata.md)

## Properties

### expectedLinksCount

> **expectedLinksCount**: `number`

Defined in: [WAProto/index.d.ts:1513](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1513)

BotPluginMetadata expectedLinksCount.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`expectedLinksCount`](../interfaces/IBotPluginMetadata.md#expectedlinkscount)

***

### pluginType

> **pluginType**: [`PluginType`](../namespaces/BotPluginMetadata/enumerations/PluginType.md)

Defined in: [WAProto/index.d.ts:1498](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1498)

BotPluginMetadata pluginType.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`pluginType`](../interfaces/IBotPluginMetadata.md#plugintype)

***

### pluginVersion

> **pluginVersion**: `number`

Defined in: [WAProto/index.d.ts:1516](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1516)

BotPluginMetadata pluginVersion.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`pluginVersion`](../interfaces/IBotPluginMetadata.md#pluginversion)

***

### profilePhotoCdnUrl

> **profilePhotoCdnUrl**: `string`

Defined in: [WAProto/index.d.ts:1504](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1504)

BotPluginMetadata profilePhotoCdnUrl.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`profilePhotoCdnUrl`](../interfaces/IBotPluginMetadata.md#profilephotocdnurl)

***

### provider

> **provider**: [`SearchProvider`](../namespaces/BotPluginMetadata/enumerations/SearchProvider.md)

Defined in: [WAProto/index.d.ts:1495](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1495)

BotPluginMetadata provider.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`provider`](../interfaces/IBotPluginMetadata.md#provider)

***

### referenceIndex

> **referenceIndex**: `number`

Defined in: [WAProto/index.d.ts:1510](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1510)

BotPluginMetadata referenceIndex.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`referenceIndex`](../interfaces/IBotPluginMetadata.md#referenceindex)

***

### searchProviderUrl

> **searchProviderUrl**: `string`

Defined in: [WAProto/index.d.ts:1507](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1507)

BotPluginMetadata searchProviderUrl.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`searchProviderUrl`](../interfaces/IBotPluginMetadata.md#searchproviderurl)

***

### thumbnailCdnUrl

> **thumbnailCdnUrl**: `string`

Defined in: [WAProto/index.d.ts:1501](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1501)

BotPluginMetadata thumbnailCdnUrl.

#### Implementation of

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md).[`thumbnailCdnUrl`](../interfaces/IBotPluginMetadata.md#thumbnailcdnurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1586](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1586)

Converts this BotPluginMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotPluginMetadata`](BotPluginMetadata.md)

Defined in: [WAProto/index.d.ts:1523](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1523)

Creates a new BotPluginMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md)

Properties to set

#### Returns

[`BotPluginMetadata`](BotPluginMetadata.md)

BotPluginMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotPluginMetadata`](BotPluginMetadata.md)

Defined in: [WAProto/index.d.ts:1549](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1549)

Decodes a BotPluginMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotPluginMetadata`](BotPluginMetadata.md)

BotPluginMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotPluginMetadata`](BotPluginMetadata.md)

Defined in: [WAProto/index.d.ts:1558](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1558)

Decodes a BotPluginMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotPluginMetadata`](BotPluginMetadata.md)

BotPluginMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1531](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1531)

Encodes the specified BotPluginMetadata message. Does not implicitly [verify](BotPluginMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md)

BotPluginMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1539](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1539)

Encodes the specified BotPluginMetadata message, length delimited. Does not implicitly [verify](BotPluginMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPluginMetadata`](../interfaces/IBotPluginMetadata.md)

BotPluginMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotPluginMetadata`](BotPluginMetadata.md)

Defined in: [WAProto/index.d.ts:1572](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1572)

Creates a BotPluginMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotPluginMetadata`](BotPluginMetadata.md)

BotPluginMetadata

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:1580](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1580)

Creates a plain object from a BotPluginMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotPluginMetadata`](BotPluginMetadata.md)

BotPluginMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1565](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1565)

Verifies a BotPluginMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
