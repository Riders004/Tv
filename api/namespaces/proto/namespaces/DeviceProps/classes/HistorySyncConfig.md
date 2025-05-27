# Class: HistorySyncConfig

Defined in: [WAProto/index.d.ts:5975](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5975)

Represents a HistorySyncConfig.

## Implements

- [`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md)

## Constructors

### new HistorySyncConfig()

> **new HistorySyncConfig**(`properties`?): [`HistorySyncConfig`](HistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:5981](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5981)

Constructs a new HistorySyncConfig.

#### Parameters

##### properties?

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md)

Properties to set

#### Returns

[`HistorySyncConfig`](HistorySyncConfig.md)

## Properties

### fullSyncDaysLimit

> **fullSyncDaysLimit**: `number`

Defined in: [WAProto/index.d.ts:5984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5984)

HistorySyncConfig fullSyncDaysLimit.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`fullSyncDaysLimit`](../interfaces/IHistorySyncConfig.md#fullsyncdayslimit)

***

### fullSyncSizeMbLimit

> **fullSyncSizeMbLimit**: `number`

Defined in: [WAProto/index.d.ts:5987](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5987)

HistorySyncConfig fullSyncSizeMbLimit.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`fullSyncSizeMbLimit`](../interfaces/IHistorySyncConfig.md#fullsyncsizemblimit)

***

### inlineInitialPayloadInE2EeMsg

> **inlineInitialPayloadInE2EeMsg**: `boolean`

Defined in: [WAProto/index.d.ts:5993](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5993)

HistorySyncConfig inlineInitialPayloadInE2EeMsg.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`inlineInitialPayloadInE2EeMsg`](../interfaces/IHistorySyncConfig.md#inlineinitialpayloadine2eemsg)

***

### recentSyncDaysLimit

> **recentSyncDaysLimit**: `number`

Defined in: [WAProto/index.d.ts:5996](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5996)

HistorySyncConfig recentSyncDaysLimit.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`recentSyncDaysLimit`](../interfaces/IHistorySyncConfig.md#recentsyncdayslimit)

***

### storageQuotaMb

> **storageQuotaMb**: `number`

Defined in: [WAProto/index.d.ts:5990](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5990)

HistorySyncConfig storageQuotaMb.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`storageQuotaMb`](../interfaces/IHistorySyncConfig.md#storagequotamb)

***

### supportBotUserAgentChatHistory

> **supportBotUserAgentChatHistory**: `boolean`

Defined in: [WAProto/index.d.ts:6002](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6002)

HistorySyncConfig supportBotUserAgentChatHistory.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`supportBotUserAgentChatHistory`](../interfaces/IHistorySyncConfig.md#supportbotuseragentchathistory)

***

### supportCagReactionsAndPolls

> **supportCagReactionsAndPolls**: `boolean`

Defined in: [WAProto/index.d.ts:6005](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6005)

HistorySyncConfig supportCagReactionsAndPolls.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`supportCagReactionsAndPolls`](../interfaces/IHistorySyncConfig.md#supportcagreactionsandpolls)

***

### supportCallLogHistory

> **supportCallLogHistory**: `boolean`

Defined in: [WAProto/index.d.ts:5999](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5999)

HistorySyncConfig supportCallLogHistory.

#### Implementation of

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md).[`supportCallLogHistory`](../interfaces/IHistorySyncConfig.md#supportcallloghistory)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6075](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6075)

Converts this HistorySyncConfig to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HistorySyncConfig`](HistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:6012](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6012)

Creates a new HistorySyncConfig instance using the specified properties.

#### Parameters

##### properties?

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md)

Properties to set

#### Returns

[`HistorySyncConfig`](HistorySyncConfig.md)

HistorySyncConfig instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HistorySyncConfig`](HistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:6038](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6038)

Decodes a HistorySyncConfig message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HistorySyncConfig`](HistorySyncConfig.md)

HistorySyncConfig

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HistorySyncConfig`](HistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:6047](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6047)

Decodes a HistorySyncConfig message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HistorySyncConfig`](HistorySyncConfig.md)

HistorySyncConfig

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6020](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6020)

Encodes the specified HistorySyncConfig message. Does not implicitly [verify](HistorySyncConfig.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md)

HistorySyncConfig message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6028](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6028)

Encodes the specified HistorySyncConfig message, length delimited. Does not implicitly [verify](HistorySyncConfig.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncConfig`](../interfaces/IHistorySyncConfig.md)

HistorySyncConfig message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HistorySyncConfig`](HistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:6061](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6061)

Creates a HistorySyncConfig message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HistorySyncConfig`](HistorySyncConfig.md)

HistorySyncConfig

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:6069](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6069)

Creates a plain object from a HistorySyncConfig message. Also converts values to other types if specified.

#### Parameters

##### message

[`HistorySyncConfig`](HistorySyncConfig.md)

HistorySyncConfig

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6054](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6054)

Verifies a HistorySyncConfig message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
