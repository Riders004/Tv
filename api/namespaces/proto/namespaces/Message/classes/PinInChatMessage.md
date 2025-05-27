# Class: PinInChatMessage

Defined in: [WAProto/index.d.ts:19926](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19926)

Represents a PinInChatMessage.

## Implements

- [`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

## Constructors

### new PinInChatMessage()

> **new PinInChatMessage**(`properties`?): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:19932](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19932)

Constructs a new PinInChatMessage.

#### Parameters

##### properties?

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

Properties to set

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:19935](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19935)

PinInChatMessage key.

#### Implementation of

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md).[`key`](../interfaces/IPinInChatMessage.md#key)

***

### senderTimestampMs

> **senderTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:19941](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19941)

PinInChatMessage senderTimestampMs.

#### Implementation of

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md).[`senderTimestampMs`](../interfaces/IPinInChatMessage.md#sendertimestampms)

***

### type

> **type**: [`Type`](../namespaces/PinInChatMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:19938](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19938)

PinInChatMessage type.

#### Implementation of

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md).[`type`](../interfaces/IPinInChatMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20011](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20011)

Converts this PinInChatMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:19948](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19948)

Creates a new PinInChatMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

Properties to set

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

PinInChatMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:19974](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19974)

Decodes a PinInChatMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

PinInChatMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:19983](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19983)

Decodes a PinInChatMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

PinInChatMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19956](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19956)

Encodes the specified PinInChatMessage message. Does not implicitly [verify](PinInChatMessage.md#verify) messages.

#### Parameters

##### message

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

PinInChatMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19964](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19964)

Encodes the specified PinInChatMessage message, length delimited. Does not implicitly [verify](PinInChatMessage.md#verify) messages.

#### Parameters

##### message

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

PinInChatMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:19997](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19997)

Creates a PinInChatMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

PinInChatMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20005](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20005)

Creates a plain object from a PinInChatMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PinInChatMessage`](PinInChatMessage.md)

PinInChatMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19990](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19990)

Verifies a PinInChatMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
