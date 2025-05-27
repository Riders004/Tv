# Class: HistorySyncOnDemandRequest

Defined in: [WAProto/index.d.ts:18965](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18965)

Represents a HistorySyncOnDemandRequest.

## Implements

- [`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

## Constructors

### new HistorySyncOnDemandRequest()

> **new HistorySyncOnDemandRequest**(`properties`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:18971](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18971)

Constructs a new HistorySyncOnDemandRequest.

#### Parameters

##### properties?

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

Properties to set

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

## Properties

### chatJid

> **chatJid**: `string`

Defined in: [WAProto/index.d.ts:18974](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18974)

HistorySyncOnDemandRequest chatJid.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`chatJid`](../interfaces/IHistorySyncOnDemandRequest.md#chatjid)

***

### oldestMsgFromMe

> **oldestMsgFromMe**: `boolean`

Defined in: [WAProto/index.d.ts:18980](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18980)

HistorySyncOnDemandRequest oldestMsgFromMe.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgFromMe`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgfromme)

***

### oldestMsgId

> **oldestMsgId**: `string`

Defined in: [WAProto/index.d.ts:18977](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18977)

HistorySyncOnDemandRequest oldestMsgId.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgId`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgid)

***

### oldestMsgTimestampMs

> **oldestMsgTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:18986](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18986)

HistorySyncOnDemandRequest oldestMsgTimestampMs.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgTimestampMs`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgtimestampms)

***

### onDemandMsgCount

> **onDemandMsgCount**: `number`

Defined in: [WAProto/index.d.ts:18983](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18983)

HistorySyncOnDemandRequest onDemandMsgCount.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`onDemandMsgCount`](../interfaces/IHistorySyncOnDemandRequest.md#ondemandmsgcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19056](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19056)

Converts this HistorySyncOnDemandRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:18993](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18993)

Creates a new HistorySyncOnDemandRequest instance using the specified properties.

#### Parameters

##### properties?

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

Properties to set

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:19019](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19019)

Decodes a HistorySyncOnDemandRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:19028](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19028)

Decodes a HistorySyncOnDemandRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19001](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19001)

Encodes the specified HistorySyncOnDemandRequest message. Does not implicitly [verify](HistorySyncOnDemandRequest.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19009](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19009)

Encodes the specified HistorySyncOnDemandRequest message, length delimited. Does not implicitly [verify](HistorySyncOnDemandRequest.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:19042](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19042)

Creates a HistorySyncOnDemandRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:19050](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19050)

Creates a plain object from a HistorySyncOnDemandRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19035](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19035)

Verifies a HistorySyncOnDemandRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
