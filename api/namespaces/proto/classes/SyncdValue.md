# Class: SyncdValue

Defined in: [WAProto/index.d.ts:34913](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34913)

Represents a SyncdValue.

## Implements

- [`ISyncdValue`](../interfaces/ISyncdValue.md)

## Constructors

### new SyncdValue()

> **new SyncdValue**(`properties`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:34919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34919)

Constructs a new SyncdValue.

#### Parameters

##### properties?

[`ISyncdValue`](../interfaces/ISyncdValue.md)

Properties to set

#### Returns

[`SyncdValue`](SyncdValue.md)

## Properties

### blob

> **blob**: `Uint8Array`

Defined in: [WAProto/index.d.ts:34922](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34922)

SyncdValue blob.

#### Implementation of

[`ISyncdValue`](../interfaces/ISyncdValue.md).[`blob`](../interfaces/ISyncdValue.md#blob)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34992](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34992)

Converts this SyncdValue to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:34929](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34929)

Creates a new SyncdValue instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdValue`](../interfaces/ISyncdValue.md)

Properties to set

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:34955](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34955)

Decodes a SyncdValue message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:34964](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34964)

Decodes a SyncdValue message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34937](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34937)

Encodes the specified SyncdValue message. Does not implicitly [verify](SyncdValue.md#verify) messages.

#### Parameters

##### message

[`ISyncdValue`](../interfaces/ISyncdValue.md)

SyncdValue message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34945](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34945)

Encodes the specified SyncdValue message, length delimited. Does not implicitly [verify](SyncdValue.md#verify) messages.

#### Parameters

##### message

[`ISyncdValue`](../interfaces/ISyncdValue.md)

SyncdValue message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:34978](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34978)

Creates a SyncdValue message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34986](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34986)

Creates a plain object from a SyncdValue message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdValue`](SyncdValue.md)

SyncdValue

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34971](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34971)

Verifies a SyncdValue message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
