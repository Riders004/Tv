# Class: SenderKeyRecordStructure

Defined in: [WAProto/index.d.ts:27650](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27650)

Represents a SenderKeyRecordStructure.

## Implements

- [`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

## Constructors

### new SenderKeyRecordStructure()

> **new SenderKeyRecordStructure**(`properties`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:27656](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27656)

Constructs a new SenderKeyRecordStructure.

#### Parameters

##### properties?

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

Properties to set

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

## Properties

### senderKeyStates

> **senderKeyStates**: [`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)[]

Defined in: [WAProto/index.d.ts:27659](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27659)

SenderKeyRecordStructure senderKeyStates.

#### Implementation of

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md).[`senderKeyStates`](../interfaces/ISenderKeyRecordStructure.md#senderkeystates)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27729](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27729)

Converts this SenderKeyRecordStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:27666](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27666)

Creates a new SenderKeyRecordStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

Properties to set

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:27692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27692)

Decodes a SenderKeyRecordStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:27701](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27701)

Decodes a SenderKeyRecordStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27674](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27674)

Encodes the specified SenderKeyRecordStructure message. Does not implicitly [verify](SenderKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

SenderKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27682](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27682)

Encodes the specified SenderKeyRecordStructure message, length delimited. Does not implicitly [verify](SenderKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

SenderKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:27715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27715)

Creates a SenderKeyRecordStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27723](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27723)

Creates a plain object from a SenderKeyRecordStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27708](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27708)

Verifies a SenderKeyRecordStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
