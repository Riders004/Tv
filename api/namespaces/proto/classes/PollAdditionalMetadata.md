# Class: PollAdditionalMetadata

Defined in: [WAProto/index.d.ts:25923](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25923)

Represents a PollAdditionalMetadata.

## Implements

- [`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

## Constructors

### new PollAdditionalMetadata()

> **new PollAdditionalMetadata**(`properties`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:25929](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25929)

Constructs a new PollAdditionalMetadata.

#### Parameters

##### properties?

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

Properties to set

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

## Properties

### pollInvalidated

> **pollInvalidated**: `boolean`

Defined in: [WAProto/index.d.ts:25932](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25932)

PollAdditionalMetadata pollInvalidated.

#### Implementation of

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md).[`pollInvalidated`](../interfaces/IPollAdditionalMetadata.md#pollinvalidated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26002](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26002)

Converts this PollAdditionalMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:25939](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25939)

Creates a new PollAdditionalMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

Properties to set

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:25965](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25965)

Decodes a PollAdditionalMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:25974](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25974)

Decodes a PollAdditionalMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25947](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25947)

Encodes the specified PollAdditionalMetadata message. Does not implicitly [verify](PollAdditionalMetadata.md#verify) messages.

#### Parameters

##### message

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

PollAdditionalMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25955](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25955)

Encodes the specified PollAdditionalMetadata message, length delimited. Does not implicitly [verify](PollAdditionalMetadata.md#verify) messages.

#### Parameters

##### message

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

PollAdditionalMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:25988](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25988)

Creates a PollAdditionalMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:25996](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25996)

Creates a plain object from a PollAdditionalMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25981](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25981)

Verifies a PollAdditionalMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
