# Class: ParticipantInfo

Defined in: [WAProto/index.d.ts:1909](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1909)

Represents a ParticipantInfo.

## Implements

- [`IParticipantInfo`](../interfaces/IParticipantInfo.md)

## Constructors

### new ParticipantInfo()

> **new ParticipantInfo**(`properties`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:1915](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1915)

Constructs a new ParticipantInfo.

#### Parameters

##### properties?

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

Properties to set

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

## Properties

### callResult

> **callResult**: [`CallResult`](../enumerations/CallResult.md)

Defined in: [WAProto/index.d.ts:1921](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1921)

ParticipantInfo callResult.

#### Implementation of

[`IParticipantInfo`](../interfaces/IParticipantInfo.md).[`callResult`](../interfaces/IParticipantInfo.md#callresult)

***

### userJid

> **userJid**: `string`

Defined in: [WAProto/index.d.ts:1918](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1918)

ParticipantInfo userJid.

#### Implementation of

[`IParticipantInfo`](../interfaces/IParticipantInfo.md).[`userJid`](../interfaces/IParticipantInfo.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1991](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1991)

Converts this ParticipantInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:1928](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1928)

Creates a new ParticipantInfo instance using the specified properties.

#### Parameters

##### properties?

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

Properties to set

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:1954](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1954)

Decodes a ParticipantInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:1963](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1963)

Decodes a ParticipantInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1936](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1936)

Encodes the specified ParticipantInfo message. Does not implicitly [verify](ParticipantInfo.md#verify) messages.

#### Parameters

##### message

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

ParticipantInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1944](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1944)

Encodes the specified ParticipantInfo message, length delimited. Does not implicitly [verify](ParticipantInfo.md#verify) messages.

#### Parameters

##### message

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

ParticipantInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:1977](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1977)

Creates a ParticipantInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:1985](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1985)

Creates a plain object from a ParticipantInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1970](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1970)

Verifies a ParticipantInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
