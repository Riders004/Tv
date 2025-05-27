# Class: PreKeySignalMessage

Defined in: [WAProto/index.d.ts:26340](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26340)

Represents a PreKeySignalMessage.

## Implements

- [`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

## Constructors

### new PreKeySignalMessage()

> **new PreKeySignalMessage**(`properties`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:26346](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26346)

Constructs a new PreKeySignalMessage.

#### Parameters

##### properties?

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

Properties to set

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

## Properties

### baseKey

> **baseKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:26358](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26358)

PreKeySignalMessage baseKey.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`baseKey`](../interfaces/IPreKeySignalMessage.md#basekey)

***

### identityKey

> **identityKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:26361](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26361)

PreKeySignalMessage identityKey.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`identityKey`](../interfaces/IPreKeySignalMessage.md#identitykey)

***

### message

> **message**: `Uint8Array`

Defined in: [WAProto/index.d.ts:26364](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26364)

PreKeySignalMessage message.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`message`](../interfaces/IPreKeySignalMessage.md#message)

***

### preKeyId

> **preKeyId**: `number`

Defined in: [WAProto/index.d.ts:26352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26352)

PreKeySignalMessage preKeyId.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`preKeyId`](../interfaces/IPreKeySignalMessage.md#prekeyid)

***

### registrationId

> **registrationId**: `number`

Defined in: [WAProto/index.d.ts:26349](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26349)

PreKeySignalMessage registrationId.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`registrationId`](../interfaces/IPreKeySignalMessage.md#registrationid)

***

### signedPreKeyId

> **signedPreKeyId**: `number`

Defined in: [WAProto/index.d.ts:26355](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26355)

PreKeySignalMessage signedPreKeyId.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`signedPreKeyId`](../interfaces/IPreKeySignalMessage.md#signedprekeyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26434](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26434)

Converts this PreKeySignalMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:26371](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26371)

Creates a new PreKeySignalMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

Properties to set

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:26397](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26397)

Decodes a PreKeySignalMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:26406](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26406)

Decodes a PreKeySignalMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26379](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26379)

Encodes the specified PreKeySignalMessage message. Does not implicitly [verify](PreKeySignalMessage.md#verify) messages.

#### Parameters

##### message

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

PreKeySignalMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26387](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26387)

Encodes the specified PreKeySignalMessage message, length delimited. Does not implicitly [verify](PreKeySignalMessage.md#verify) messages.

#### Parameters

##### message

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

PreKeySignalMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:26420](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26420)

Creates a PreKeySignalMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:26428](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26428)

Creates a plain object from a PreKeySignalMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26413](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26413)

Verifies a PreKeySignalMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
