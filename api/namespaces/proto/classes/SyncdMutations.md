# Class: SyncdMutations

Defined in: [WAProto/index.d.ts:34475](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34475)

Represents a SyncdMutations.

## Implements

- [`ISyncdMutations`](../interfaces/ISyncdMutations.md)

## Constructors

### new SyncdMutations()

> **new SyncdMutations**(`properties`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:34481](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34481)

Constructs a new SyncdMutations.

#### Parameters

##### properties?

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

Properties to set

#### Returns

[`SyncdMutations`](SyncdMutations.md)

## Properties

### mutations

> **mutations**: [`ISyncdMutation`](../interfaces/ISyncdMutation.md)[]

Defined in: [WAProto/index.d.ts:34484](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34484)

SyncdMutations mutations.

#### Implementation of

[`ISyncdMutations`](../interfaces/ISyncdMutations.md).[`mutations`](../interfaces/ISyncdMutations.md#mutations)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34554](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34554)

Converts this SyncdMutations to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:34491](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34491)

Creates a new SyncdMutations instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

Properties to set

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:34517](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34517)

Decodes a SyncdMutations message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:34526](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34526)

Decodes a SyncdMutations message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34499](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34499)

Encodes the specified SyncdMutations message. Does not implicitly [verify](SyncdMutations.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

SyncdMutations message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34507](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34507)

Encodes the specified SyncdMutations message, length delimited. Does not implicitly [verify](SyncdMutations.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

SyncdMutations message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:34540](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34540)

Creates a SyncdMutations message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34548](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34548)

Creates a plain object from a SyncdMutations message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34533](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34533)

Verifies a SyncdMutations message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
