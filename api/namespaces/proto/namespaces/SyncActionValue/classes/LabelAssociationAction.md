# Class: LabelAssociationAction

Defined in: [WAProto/index.d.ts:31459](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31459)

Represents a LabelAssociationAction.

## Implements

- [`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

## Constructors

### new LabelAssociationAction()

> **new LabelAssociationAction**(`properties`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:31465](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31465)

Constructs a new LabelAssociationAction.

#### Parameters

##### properties?

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

Properties to set

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

## Properties

### labeled

> **labeled**: `boolean`

Defined in: [WAProto/index.d.ts:31468](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31468)

LabelAssociationAction labeled.

#### Implementation of

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md).[`labeled`](../interfaces/ILabelAssociationAction.md#labeled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31538](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31538)

Converts this LabelAssociationAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:31475](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31475)

Creates a new LabelAssociationAction instance using the specified properties.

#### Parameters

##### properties?

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

Properties to set

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:31501](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31501)

Decodes a LabelAssociationAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:31510](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31510)

Decodes a LabelAssociationAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31483](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31483)

Encodes the specified LabelAssociationAction message. Does not implicitly [verify](LabelAssociationAction.md#verify) messages.

#### Parameters

##### message

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

LabelAssociationAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31491](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31491)

Encodes the specified LabelAssociationAction message, length delimited. Does not implicitly [verify](LabelAssociationAction.md#verify) messages.

#### Parameters

##### message

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

LabelAssociationAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:31524](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31524)

Creates a LabelAssociationAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31532](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31532)

Creates a plain object from a LabelAssociationAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31517](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31517)

Verifies a LabelAssociationAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
