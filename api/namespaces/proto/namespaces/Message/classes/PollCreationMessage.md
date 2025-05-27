# Class: PollCreationMessage

Defined in: [WAProto/index.d.ts:20142](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20142)

Represents a PollCreationMessage.

## Implements

- [`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

## Constructors

### new PollCreationMessage()

> **new PollCreationMessage**(`properties`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:20148](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20148)

Constructs a new PollCreationMessage.

#### Parameters

##### properties?

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

Properties to set

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:20163](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20163)

PollCreationMessage contextInfo.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`contextInfo`](../interfaces/IPollCreationMessage.md#contextinfo)

***

### encKey

> **encKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:20151](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20151)

PollCreationMessage encKey.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`encKey`](../interfaces/IPollCreationMessage.md#enckey)

***

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:20154](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20154)

PollCreationMessage name.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`name`](../interfaces/IPollCreationMessage.md#name)

***

### options

> **options**: [`IOption`](../namespaces/PollCreationMessage/interfaces/IOption.md)[]

Defined in: [WAProto/index.d.ts:20157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20157)

PollCreationMessage options.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`options`](../interfaces/IPollCreationMessage.md#options)

***

### selectableOptionsCount

> **selectableOptionsCount**: `number`

Defined in: [WAProto/index.d.ts:20160](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20160)

PollCreationMessage selectableOptionsCount.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`selectableOptionsCount`](../interfaces/IPollCreationMessage.md#selectableoptionscount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20233](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20233)

Converts this PollCreationMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:20170](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20170)

Creates a new PollCreationMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

Properties to set

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:20196](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20196)

Decodes a PollCreationMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:20205](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20205)

Decodes a PollCreationMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20178](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20178)

Encodes the specified PollCreationMessage message. Does not implicitly [verify](PollCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

PollCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20186](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20186)

Encodes the specified PollCreationMessage message, length delimited. Does not implicitly [verify](PollCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

PollCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:20219](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20219)

Creates a PollCreationMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20227](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20227)

Creates a plain object from a PollCreationMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20212](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20212)

Verifies a PollCreationMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
