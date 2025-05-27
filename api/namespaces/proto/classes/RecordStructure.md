# Class: RecordStructure

Defined in: [WAProto/index.d.ts:27257](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27257)

Represents a RecordStructure.

## Implements

- [`IRecordStructure`](../interfaces/IRecordStructure.md)

## Constructors

### new RecordStructure()

> **new RecordStructure**(`properties`?): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:27263](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27263)

Constructs a new RecordStructure.

#### Parameters

##### properties?

[`IRecordStructure`](../interfaces/IRecordStructure.md)

Properties to set

#### Returns

[`RecordStructure`](RecordStructure.md)

## Properties

### currentSession?

> `optional` **currentSession**: `null` \| [`ISessionStructure`](../interfaces/ISessionStructure.md)

Defined in: [WAProto/index.d.ts:27266](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27266)

RecordStructure currentSession.

#### Implementation of

[`IRecordStructure`](../interfaces/IRecordStructure.md).[`currentSession`](../interfaces/IRecordStructure.md#currentsession)

***

### previousSessions

> **previousSessions**: [`ISessionStructure`](../interfaces/ISessionStructure.md)[]

Defined in: [WAProto/index.d.ts:27269](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27269)

RecordStructure previousSessions.

#### Implementation of

[`IRecordStructure`](../interfaces/IRecordStructure.md).[`previousSessions`](../interfaces/IRecordStructure.md#previoussessions)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27339](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27339)

Converts this RecordStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:27276](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27276)

Creates a new RecordStructure instance using the specified properties.

#### Parameters

##### properties?

[`IRecordStructure`](../interfaces/IRecordStructure.md)

Properties to set

#### Returns

[`RecordStructure`](RecordStructure.md)

RecordStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:27302](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27302)

Decodes a RecordStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RecordStructure`](RecordStructure.md)

RecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:27311](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27311)

Decodes a RecordStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RecordStructure`](RecordStructure.md)

RecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27284](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27284)

Encodes the specified RecordStructure message. Does not implicitly [verify](RecordStructure.md#verify) messages.

#### Parameters

##### message

[`IRecordStructure`](../interfaces/IRecordStructure.md)

RecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27292](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27292)

Encodes the specified RecordStructure message, length delimited. Does not implicitly [verify](RecordStructure.md#verify) messages.

#### Parameters

##### message

[`IRecordStructure`](../interfaces/IRecordStructure.md)

RecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:27325](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27325)

Creates a RecordStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RecordStructure`](RecordStructure.md)

RecordStructure

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27333](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27333)

Creates a plain object from a RecordStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`RecordStructure`](RecordStructure.md)

RecordStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27318](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27318)

Verifies a RecordStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
