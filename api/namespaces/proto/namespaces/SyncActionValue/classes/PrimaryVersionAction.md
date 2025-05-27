# Class: PrimaryVersionAction

Defined in: [WAProto/index.d.ts:32715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32715)

Represents a PrimaryVersionAction.

## Implements

- [`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

## Constructors

### new PrimaryVersionAction()

> **new PrimaryVersionAction**(`properties`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:32721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32721)

Constructs a new PrimaryVersionAction.

#### Parameters

##### properties?

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

Properties to set

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

## Properties

### version

> **version**: `string`

Defined in: [WAProto/index.d.ts:32724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32724)

PrimaryVersionAction version.

#### Implementation of

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md).[`version`](../interfaces/IPrimaryVersionAction.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32794)

Converts this PrimaryVersionAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:32731](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32731)

Creates a new PrimaryVersionAction instance using the specified properties.

#### Parameters

##### properties?

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

Properties to set

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:32757](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32757)

Decodes a PrimaryVersionAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:32766](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32766)

Decodes a PrimaryVersionAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32739)

Encodes the specified PrimaryVersionAction message. Does not implicitly [verify](PrimaryVersionAction.md#verify) messages.

#### Parameters

##### message

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

PrimaryVersionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32747](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32747)

Encodes the specified PrimaryVersionAction message, length delimited. Does not implicitly [verify](PrimaryVersionAction.md#verify) messages.

#### Parameters

##### message

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

PrimaryVersionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:32780](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32780)

Creates a PrimaryVersionAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32788](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32788)

Creates a plain object from a PrimaryVersionAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32773](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32773)

Verifies a PrimaryVersionAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
