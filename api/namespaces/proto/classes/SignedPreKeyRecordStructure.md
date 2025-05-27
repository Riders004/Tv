# Class: SignedPreKeyRecordStructure

Defined in: [WAProto/index.d.ts:29057](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29057)

Represents a SignedPreKeyRecordStructure.

## Implements

- [`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

## Constructors

### new SignedPreKeyRecordStructure()

> **new SignedPreKeyRecordStructure**(`properties`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:29063](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29063)

Constructs a new SignedPreKeyRecordStructure.

#### Parameters

##### properties?

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

Properties to set

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

## Properties

### id

> **id**: `number`

Defined in: [WAProto/index.d.ts:29066](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29066)

SignedPreKeyRecordStructure id.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`id`](../interfaces/ISignedPreKeyRecordStructure.md#id)

***

### privateKey

> **privateKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:29072](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29072)

SignedPreKeyRecordStructure privateKey.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`privateKey`](../interfaces/ISignedPreKeyRecordStructure.md#privatekey)

***

### publicKey

> **publicKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:29069](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29069)

SignedPreKeyRecordStructure publicKey.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`publicKey`](../interfaces/ISignedPreKeyRecordStructure.md#publickey)

***

### signature

> **signature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:29075](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29075)

SignedPreKeyRecordStructure signature.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`signature`](../interfaces/ISignedPreKeyRecordStructure.md#signature)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:29078](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29078)

SignedPreKeyRecordStructure timestamp.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`timestamp`](../interfaces/ISignedPreKeyRecordStructure.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29148](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29148)

Converts this SignedPreKeyRecordStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:29085](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29085)

Creates a new SignedPreKeyRecordStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

Properties to set

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:29111](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29111)

Decodes a SignedPreKeyRecordStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:29120](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29120)

Decodes a SignedPreKeyRecordStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29093](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29093)

Encodes the specified SignedPreKeyRecordStructure message. Does not implicitly [verify](SignedPreKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29101](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29101)

Encodes the specified SignedPreKeyRecordStructure message, length delimited. Does not implicitly [verify](SignedPreKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:29134](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29134)

Creates a SignedPreKeyRecordStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:29142](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29142)

Creates a plain object from a SignedPreKeyRecordStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29127](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29127)

Verifies a SignedPreKeyRecordStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
