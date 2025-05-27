# Class: PeerDataOperationResult

Defined in: [WAProto/index.d.ts:19457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19457)

Represents a PeerDataOperationResult.

## Implements

- [`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md)

## Constructors

### new PeerDataOperationResult()

> **new PeerDataOperationResult**(`properties`?): [`PeerDataOperationResult`](PeerDataOperationResult.md)

Defined in: [WAProto/index.d.ts:19463](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19463)

Constructs a new PeerDataOperationResult.

#### Parameters

##### properties?

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md)

Properties to set

#### Returns

[`PeerDataOperationResult`](PeerDataOperationResult.md)

## Properties

### linkPreviewResponse?

> `optional` **linkPreviewResponse**: `null` \| [`ILinkPreviewResponse`](../namespaces/PeerDataOperationResult/interfaces/ILinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:19472](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19472)

PeerDataOperationResult linkPreviewResponse.

#### Implementation of

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md).[`linkPreviewResponse`](../interfaces/IPeerDataOperationResult.md#linkpreviewresponse)

***

### mediaUploadResult

> **mediaUploadResult**: [`ResultType`](../../../../MediaRetryNotification/enumerations/ResultType.md)

Defined in: [WAProto/index.d.ts:19466](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19466)

PeerDataOperationResult mediaUploadResult.

#### Implementation of

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md).[`mediaUploadResult`](../interfaces/IPeerDataOperationResult.md#mediauploadresult)

***

### placeholderMessageResendResponse?

> `optional` **placeholderMessageResendResponse**: `null` \| [`IPlaceholderMessageResendResponse`](../namespaces/PeerDataOperationResult/interfaces/IPlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:19475](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19475)

PeerDataOperationResult placeholderMessageResendResponse.

#### Implementation of

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md).[`placeholderMessageResendResponse`](../interfaces/IPeerDataOperationResult.md#placeholdermessageresendresponse)

***

### stickerMessage?

> `optional` **stickerMessage**: `null` \| [`IStickerMessage`](../../../interfaces/IStickerMessage.md)

Defined in: [WAProto/index.d.ts:19469](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19469)

PeerDataOperationResult stickerMessage.

#### Implementation of

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md).[`stickerMessage`](../interfaces/IPeerDataOperationResult.md#stickermessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19545](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19545)

Converts this PeerDataOperationResult to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PeerDataOperationResult`](PeerDataOperationResult.md)

Defined in: [WAProto/index.d.ts:19482](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19482)

Creates a new PeerDataOperationResult instance using the specified properties.

#### Parameters

##### properties?

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md)

Properties to set

#### Returns

[`PeerDataOperationResult`](PeerDataOperationResult.md)

PeerDataOperationResult instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PeerDataOperationResult`](PeerDataOperationResult.md)

Defined in: [WAProto/index.d.ts:19508](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19508)

Decodes a PeerDataOperationResult message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PeerDataOperationResult`](PeerDataOperationResult.md)

PeerDataOperationResult

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PeerDataOperationResult`](PeerDataOperationResult.md)

Defined in: [WAProto/index.d.ts:19517](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19517)

Decodes a PeerDataOperationResult message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PeerDataOperationResult`](PeerDataOperationResult.md)

PeerDataOperationResult

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19490](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19490)

Encodes the specified PeerDataOperationResult message. Does not implicitly [verify](PeerDataOperationResult.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md)

PeerDataOperationResult message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19498](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19498)

Encodes the specified PeerDataOperationResult message, length delimited. Does not implicitly [verify](PeerDataOperationResult.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationResult`](../interfaces/IPeerDataOperationResult.md)

PeerDataOperationResult message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PeerDataOperationResult`](PeerDataOperationResult.md)

Defined in: [WAProto/index.d.ts:19531](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19531)

Creates a PeerDataOperationResult message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PeerDataOperationResult`](PeerDataOperationResult.md)

PeerDataOperationResult

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:19539](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19539)

Creates a plain object from a PeerDataOperationResult message. Also converts values to other types if specified.

#### Parameters

##### message

[`PeerDataOperationResult`](PeerDataOperationResult.md)

PeerDataOperationResult

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19524](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19524)

Verifies a PeerDataOperationResult message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
