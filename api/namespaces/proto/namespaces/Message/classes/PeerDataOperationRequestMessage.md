# Class: PeerDataOperationRequestMessage

Defined in: [WAProto/index.d.ts:18849](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18849)

Represents a PeerDataOperationRequestMessage.

## Implements

- [`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

## Constructors

### new PeerDataOperationRequestMessage()

> **new PeerDataOperationRequestMessage**(`properties`?): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:18855](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18855)

Constructs a new PeerDataOperationRequestMessage.

#### Parameters

##### properties?

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

## Properties

### historySyncOnDemandRequest?

> `optional` **historySyncOnDemandRequest**: `null` \| [`IHistorySyncOnDemandRequest`](../namespaces/PeerDataOperationRequestMessage/interfaces/IHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:18867](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18867)

PeerDataOperationRequestMessage historySyncOnDemandRequest.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`historySyncOnDemandRequest`](../interfaces/IPeerDataOperationRequestMessage.md#historysyncondemandrequest)

***

### peerDataOperationRequestType

> **peerDataOperationRequestType**: [`PeerDataOperationRequestType`](../enumerations/PeerDataOperationRequestType.md)

Defined in: [WAProto/index.d.ts:18858](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18858)

PeerDataOperationRequestMessage peerDataOperationRequestType.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`peerDataOperationRequestType`](../interfaces/IPeerDataOperationRequestMessage.md#peerdataoperationrequesttype)

***

### placeholderMessageResendRequest

> **placeholderMessageResendRequest**: [`IPlaceholderMessageResendRequest`](../namespaces/PeerDataOperationRequestMessage/interfaces/IPlaceholderMessageResendRequest.md)[]

Defined in: [WAProto/index.d.ts:18870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18870)

PeerDataOperationRequestMessage placeholderMessageResendRequest.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`placeholderMessageResendRequest`](../interfaces/IPeerDataOperationRequestMessage.md#placeholdermessageresendrequest)

***

### requestStickerReupload

> **requestStickerReupload**: [`IRequestStickerReupload`](../namespaces/PeerDataOperationRequestMessage/interfaces/IRequestStickerReupload.md)[]

Defined in: [WAProto/index.d.ts:18861](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18861)

PeerDataOperationRequestMessage requestStickerReupload.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`requestStickerReupload`](../interfaces/IPeerDataOperationRequestMessage.md#requeststickerreupload)

***

### requestUrlPreview

> **requestUrlPreview**: [`IRequestUrlPreview`](../namespaces/PeerDataOperationRequestMessage/interfaces/IRequestUrlPreview.md)[]

Defined in: [WAProto/index.d.ts:18864](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18864)

PeerDataOperationRequestMessage requestUrlPreview.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`requestUrlPreview`](../interfaces/IPeerDataOperationRequestMessage.md#requesturlpreview)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:18940](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18940)

Converts this PeerDataOperationRequestMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:18877](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18877)

Creates a new PeerDataOperationRequestMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:18903](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18903)

Decodes a PeerDataOperationRequestMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:18912](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18912)

Decodes a PeerDataOperationRequestMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18885](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18885)

Encodes the specified PeerDataOperationRequestMessage message. Does not implicitly [verify](PeerDataOperationRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18893](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18893)

Encodes the specified PeerDataOperationRequestMessage message, length delimited. Does not implicitly [verify](PeerDataOperationRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:18926](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18926)

Creates a PeerDataOperationRequestMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:18934](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18934)

Creates a plain object from a PeerDataOperationRequestMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:18919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18919)

Verifies a PeerDataOperationRequestMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
