# Class: SyncdPatch

Defined in: [WAProto/index.d.ts:34589](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34589)

Represents a SyncdPatch.

## Implements

- [`ISyncdPatch`](../interfaces/ISyncdPatch.md)

## Constructors

### new SyncdPatch()

> **new SyncdPatch**(`properties`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:34595](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34595)

Constructs a new SyncdPatch.

#### Parameters

##### properties?

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

Properties to set

#### Returns

[`SyncdPatch`](SyncdPatch.md)

## Properties

### clientDebugData

> **clientDebugData**: `Uint8Array`

Defined in: [WAProto/index.d.ts:34622](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34622)

SyncdPatch clientDebugData.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`clientDebugData`](../interfaces/ISyncdPatch.md#clientdebugdata)

***

### deviceIndex

> **deviceIndex**: `number`

Defined in: [WAProto/index.d.ts:34619](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34619)

SyncdPatch deviceIndex.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`deviceIndex`](../interfaces/ISyncdPatch.md#deviceindex)

***

### exitCode?

> `optional` **exitCode**: `null` \| [`IExitCode`](../interfaces/IExitCode.md)

Defined in: [WAProto/index.d.ts:34616](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34616)

SyncdPatch exitCode.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`exitCode`](../interfaces/ISyncdPatch.md#exitcode)

***

### externalMutations?

> `optional` **externalMutations**: `null` \| [`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:34604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34604)

SyncdPatch externalMutations.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`externalMutations`](../interfaces/ISyncdPatch.md#externalmutations)

***

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:34613](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34613)

SyncdPatch keyId.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`keyId`](../interfaces/ISyncdPatch.md#keyid)

***

### mutations

> **mutations**: [`ISyncdMutation`](../interfaces/ISyncdMutation.md)[]

Defined in: [WAProto/index.d.ts:34601](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34601)

SyncdPatch mutations.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`mutations`](../interfaces/ISyncdPatch.md#mutations)

***

### patchMac

> **patchMac**: `Uint8Array`

Defined in: [WAProto/index.d.ts:34610](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34610)

SyncdPatch patchMac.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`patchMac`](../interfaces/ISyncdPatch.md#patchmac)

***

### snapshotMac

> **snapshotMac**: `Uint8Array`

Defined in: [WAProto/index.d.ts:34607](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34607)

SyncdPatch snapshotMac.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`snapshotMac`](../interfaces/ISyncdPatch.md#snapshotmac)

***

### version?

> `optional` **version**: `null` \| [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Defined in: [WAProto/index.d.ts:34598](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34598)

SyncdPatch version.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`version`](../interfaces/ISyncdPatch.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34692)

Converts this SyncdPatch to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:34629](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34629)

Creates a new SyncdPatch instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

Properties to set

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:34655](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34655)

Decodes a SyncdPatch message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:34664](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34664)

Decodes a SyncdPatch message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34637](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34637)

Encodes the specified SyncdPatch message. Does not implicitly [verify](SyncdPatch.md#verify) messages.

#### Parameters

##### message

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

SyncdPatch message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34645](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34645)

Encodes the specified SyncdPatch message, length delimited. Does not implicitly [verify](SyncdPatch.md#verify) messages.

#### Parameters

##### message

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

SyncdPatch message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:34678](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34678)

Creates a SyncdPatch message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34686](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34686)

Creates a plain object from a SyncdPatch message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34671](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34671)

Verifies a SyncdPatch message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
