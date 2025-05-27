# Class: LabelEditAction

Defined in: [WAProto/index.d.ts:31561](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31561)

Represents a LabelEditAction.

## Implements

- [`ILabelEditAction`](../interfaces/ILabelEditAction.md)

## Constructors

### new LabelEditAction()

> **new LabelEditAction**(`properties`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:31567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31567)

Constructs a new LabelEditAction.

#### Parameters

##### properties?

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

Properties to set

#### Returns

[`LabelEditAction`](LabelEditAction.md)

## Properties

### color

> **color**: `number`

Defined in: [WAProto/index.d.ts:31573](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31573)

LabelEditAction color.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`color`](../interfaces/ILabelEditAction.md#color)

***

### deleted

> **deleted**: `boolean`

Defined in: [WAProto/index.d.ts:31579](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31579)

LabelEditAction deleted.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`deleted`](../interfaces/ILabelEditAction.md#deleted)

***

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:31570](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31570)

LabelEditAction name.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`name`](../interfaces/ILabelEditAction.md#name)

***

### orderIndex

> **orderIndex**: `number`

Defined in: [WAProto/index.d.ts:31582](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31582)

LabelEditAction orderIndex.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`orderIndex`](../interfaces/ILabelEditAction.md#orderindex)

***

### predefinedId

> **predefinedId**: `number`

Defined in: [WAProto/index.d.ts:31576](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31576)

LabelEditAction predefinedId.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`predefinedId`](../interfaces/ILabelEditAction.md#predefinedid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31652](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31652)

Converts this LabelEditAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:31589](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31589)

Creates a new LabelEditAction instance using the specified properties.

#### Parameters

##### properties?

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

Properties to set

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:31615](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31615)

Decodes a LabelEditAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:31624](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31624)

Decodes a LabelEditAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31597](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31597)

Encodes the specified LabelEditAction message. Does not implicitly [verify](LabelEditAction.md#verify) messages.

#### Parameters

##### message

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

LabelEditAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31605](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31605)

Encodes the specified LabelEditAction message, length delimited. Does not implicitly [verify](LabelEditAction.md#verify) messages.

#### Parameters

##### message

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

LabelEditAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:31638](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31638)

Creates a LabelEditAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31646](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31646)

Creates a plain object from a LabelEditAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31631](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31631)

Verifies a LabelEditAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
