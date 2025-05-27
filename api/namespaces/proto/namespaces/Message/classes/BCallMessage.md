# Class: BCallMessage

Defined in: [WAProto/index.d.ts:10959](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10959)

Represents a BCallMessage.

## Implements

- [`IBCallMessage`](../interfaces/IBCallMessage.md)

## Constructors

### new BCallMessage()

> **new BCallMessage**(`properties`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:10965](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10965)

Constructs a new BCallMessage.

#### Parameters

##### properties?

[`IBCallMessage`](../interfaces/IBCallMessage.md)

Properties to set

#### Returns

[`BCallMessage`](BCallMessage.md)

## Properties

### caption

> **caption**: `string`

Defined in: [WAProto/index.d.ts:10977](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10977)

BCallMessage caption.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`caption`](../interfaces/IBCallMessage.md#caption)

***

### masterKey

> **masterKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:10974](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10974)

BCallMessage masterKey.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`masterKey`](../interfaces/IBCallMessage.md#masterkey)

***

### mediaType

> **mediaType**: [`MediaType`](../namespaces/BCallMessage/enumerations/MediaType.md)

Defined in: [WAProto/index.d.ts:10971](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10971)

BCallMessage mediaType.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`mediaType`](../interfaces/IBCallMessage.md#mediatype)

***

### sessionId

> **sessionId**: `string`

Defined in: [WAProto/index.d.ts:10968](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10968)

BCallMessage sessionId.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`sessionId`](../interfaces/IBCallMessage.md#sessionid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11047](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11047)

Converts this BCallMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:10984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10984)

Creates a new BCallMessage instance using the specified properties.

#### Parameters

##### properties?

[`IBCallMessage`](../interfaces/IBCallMessage.md)

Properties to set

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:11010](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11010)

Decodes a BCallMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:11019](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11019)

Decodes a BCallMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10992](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10992)

Encodes the specified BCallMessage message. Does not implicitly [verify](BCallMessage.md#verify) messages.

#### Parameters

##### message

[`IBCallMessage`](../interfaces/IBCallMessage.md)

BCallMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11000](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11000)

Encodes the specified BCallMessage message, length delimited. Does not implicitly [verify](BCallMessage.md#verify) messages.

#### Parameters

##### message

[`IBCallMessage`](../interfaces/IBCallMessage.md)

BCallMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:11033](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11033)

Creates a BCallMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11041](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11041)

Creates a plain object from a BCallMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`BCallMessage`](BCallMessage.md)

BCallMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11026](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11026)

Verifies a BCallMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
