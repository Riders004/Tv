# Class: PeerDataOperationRequestResponseMessage

Defined in: [WAProto/index.d.ts:19350](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19350)

Represents a PeerDataOperationRequestResponseMessage.

## Implements

- [`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

## Constructors

### new PeerDataOperationRequestResponseMessage()

> **new PeerDataOperationRequestResponseMessage**(`properties`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:19356](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19356)

Constructs a new PeerDataOperationRequestResponseMessage.

#### Parameters

##### properties?

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

## Properties

### peerDataOperationRequestType

> **peerDataOperationRequestType**: [`PeerDataOperationRequestType`](../enumerations/PeerDataOperationRequestType.md)

Defined in: [WAProto/index.d.ts:19359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19359)

PeerDataOperationRequestResponseMessage peerDataOperationRequestType.

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`peerDataOperationRequestType`](../interfaces/IPeerDataOperationRequestResponseMessage.md#peerdataoperationrequesttype)

***

### peerDataOperationResult

> **peerDataOperationResult**: [`IPeerDataOperationResult`](../namespaces/PeerDataOperationRequestResponseMessage/interfaces/IPeerDataOperationResult.md)[]

Defined in: [WAProto/index.d.ts:19365](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19365)

PeerDataOperationRequestResponseMessage peerDataOperationResult.

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`peerDataOperationResult`](../interfaces/IPeerDataOperationRequestResponseMessage.md#peerdataoperationresult)

***

### stanzaId

> **stanzaId**: `string`

Defined in: [WAProto/index.d.ts:19362](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19362)

PeerDataOperationRequestResponseMessage stanzaId.

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`stanzaId`](../interfaces/IPeerDataOperationRequestResponseMessage.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19435](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19435)

Converts this PeerDataOperationRequestResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:19372](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19372)

Creates a new PeerDataOperationRequestResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:19398](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19398)

Decodes a PeerDataOperationRequestResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:19407](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19407)

Decodes a PeerDataOperationRequestResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19380](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19380)

Encodes the specified PeerDataOperationRequestResponseMessage message. Does not implicitly [verify](PeerDataOperationRequestResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19388](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19388)

Encodes the specified PeerDataOperationRequestResponseMessage message, length delimited. Does not implicitly [verify](PeerDataOperationRequestResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:19421](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19421)

Creates a PeerDataOperationRequestResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:19429](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19429)

Creates a plain object from a PeerDataOperationRequestResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19414](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19414)

Verifies a PeerDataOperationRequestResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
