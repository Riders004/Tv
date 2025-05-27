# Class: PrimaryFeature

Defined in: [WAProto/index.d.ts:32625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32625)

Represents a PrimaryFeature.

## Implements

- [`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

## Constructors

### new PrimaryFeature()

> **new PrimaryFeature**(`properties`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:32631](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32631)

Constructs a new PrimaryFeature.

#### Parameters

##### properties?

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

Properties to set

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

## Properties

### flags

> **flags**: `string`[]

Defined in: [WAProto/index.d.ts:32634](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32634)

PrimaryFeature flags.

#### Implementation of

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md).[`flags`](../interfaces/IPrimaryFeature.md#flags)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32704](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32704)

Converts this PrimaryFeature to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:32641](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32641)

Creates a new PrimaryFeature instance using the specified properties.

#### Parameters

##### properties?

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

Properties to set

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:32667](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32667)

Decodes a PrimaryFeature message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:32676](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32676)

Decodes a PrimaryFeature message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32649](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32649)

Encodes the specified PrimaryFeature message. Does not implicitly [verify](PrimaryFeature.md#verify) messages.

#### Parameters

##### message

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

PrimaryFeature message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32657](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32657)

Encodes the specified PrimaryFeature message, length delimited. Does not implicitly [verify](PrimaryFeature.md#verify) messages.

#### Parameters

##### message

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

PrimaryFeature message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:32690](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32690)

Creates a PrimaryFeature message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32698](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32698)

Creates a plain object from a PrimaryFeature message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrimaryFeature`](PrimaryFeature.md)

PrimaryFeature

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32683](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32683)

Verifies a PrimaryFeature message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
