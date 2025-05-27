# Class: KeepInChatMessage

Defined in: [WAProto/index.d.ts:16968](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16968)

Represents a KeepInChatMessage.

## Implements

- [`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

## Constructors

### new KeepInChatMessage()

> **new KeepInChatMessage**(`properties`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:16974](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16974)

Constructs a new KeepInChatMessage.

#### Parameters

##### properties?

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

Properties to set

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

## Properties

### keepType

> **keepType**: [`KeepType`](../../../enumerations/KeepType.md)

Defined in: [WAProto/index.d.ts:16980](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16980)

KeepInChatMessage keepType.

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`keepType`](../interfaces/IKeepInChatMessage.md#keeptype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:16977](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16977)

KeepInChatMessage key.

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`key`](../interfaces/IKeepInChatMessage.md#key)

***

### timestampMs

> **timestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:16983](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16983)

KeepInChatMessage timestampMs.

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`timestampMs`](../interfaces/IKeepInChatMessage.md#timestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17053](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17053)

Converts this KeepInChatMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:16990](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16990)

Creates a new KeepInChatMessage instance using the specified properties.

#### Parameters

##### properties?

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

Properties to set

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:17016](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17016)

Decodes a KeepInChatMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:17025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17025)

Decodes a KeepInChatMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16998](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16998)

Encodes the specified KeepInChatMessage message. Does not implicitly [verify](KeepInChatMessage.md#verify) messages.

#### Parameters

##### message

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

KeepInChatMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17006](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17006)

Encodes the specified KeepInChatMessage message, length delimited. Does not implicitly [verify](KeepInChatMessage.md#verify) messages.

#### Parameters

##### message

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

KeepInChatMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:17039](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17039)

Creates a KeepInChatMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17047](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17047)

Creates a plain object from a KeepInChatMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17032](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17032)

Verifies a KeepInChatMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
