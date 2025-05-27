# Class: PinInChat

Defined in: [WAProto/index.d.ts:25703](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25703)

Represents a PinInChat.

## Implements

- [`IPinInChat`](../interfaces/IPinInChat.md)

## Constructors

### new PinInChat()

> **new PinInChat**(`properties`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:25709](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25709)

Constructs a new PinInChat.

#### Parameters

##### properties?

[`IPinInChat`](../interfaces/IPinInChat.md)

Properties to set

#### Returns

[`PinInChat`](PinInChat.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:25715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25715)

PinInChat key.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`key`](../interfaces/IPinInChat.md#key)

***

### messageAddOnContextInfo?

> `optional` **messageAddOnContextInfo**: `null` \| [`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:25724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25724)

PinInChat messageAddOnContextInfo.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`messageAddOnContextInfo`](../interfaces/IPinInChat.md#messageaddoncontextinfo)

***

### senderTimestampMs

> **senderTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:25718](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25718)

PinInChat senderTimestampMs.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`senderTimestampMs`](../interfaces/IPinInChat.md#sendertimestampms)

***

### serverTimestampMs

> **serverTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:25721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25721)

PinInChat serverTimestampMs.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`serverTimestampMs`](../interfaces/IPinInChat.md#servertimestampms)

***

### type

> **type**: [`Type`](../namespaces/PinInChat/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:25712](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25712)

PinInChat type.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`type`](../interfaces/IPinInChat.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25794)

Converts this PinInChat to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:25731](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25731)

Creates a new PinInChat instance using the specified properties.

#### Parameters

##### properties?

[`IPinInChat`](../interfaces/IPinInChat.md)

Properties to set

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:25757](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25757)

Decodes a PinInChat message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:25766](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25766)

Decodes a PinInChat message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25739)

Encodes the specified PinInChat message. Does not implicitly [verify](PinInChat.md#verify) messages.

#### Parameters

##### message

[`IPinInChat`](../interfaces/IPinInChat.md)

PinInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25747](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25747)

Encodes the specified PinInChat message, length delimited. Does not implicitly [verify](PinInChat.md#verify) messages.

#### Parameters

##### message

[`IPinInChat`](../interfaces/IPinInChat.md)

PinInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:25780](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25780)

Creates a PinInChat message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:25788](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25788)

Creates a plain object from a PinInChat message. Also converts values to other types if specified.

#### Parameters

##### message

[`PinInChat`](PinInChat.md)

PinInChat

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25773](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25773)

Verifies a PinInChat message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
