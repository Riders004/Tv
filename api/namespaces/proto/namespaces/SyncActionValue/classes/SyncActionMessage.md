# Class: SyncActionMessage

Defined in: [WAProto/index.d.ts:33814](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33814)

Represents a SyncActionMessage.

## Implements

- [`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

## Constructors

### new SyncActionMessage()

> **new SyncActionMessage**(`properties`?): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:33820](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33820)

Constructs a new SyncActionMessage.

#### Parameters

##### properties?

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

Properties to set

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:33823](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33823)

SyncActionMessage key.

#### Implementation of

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md).[`key`](../interfaces/ISyncActionMessage.md#key)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:33826](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33826)

SyncActionMessage timestamp.

#### Implementation of

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md).[`timestamp`](../interfaces/ISyncActionMessage.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33896](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33896)

Converts this SyncActionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:33833](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33833)

Creates a new SyncActionMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

Properties to set

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

SyncActionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:33859](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33859)

Decodes a SyncActionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

SyncActionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:33868](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33868)

Decodes a SyncActionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

SyncActionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33841](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33841)

Encodes the specified SyncActionMessage message. Does not implicitly [verify](SyncActionMessage.md#verify) messages.

#### Parameters

##### message

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

SyncActionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33849](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33849)

Encodes the specified SyncActionMessage message, length delimited. Does not implicitly [verify](SyncActionMessage.md#verify) messages.

#### Parameters

##### message

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

SyncActionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:33882](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33882)

Creates a SyncActionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

SyncActionMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33890](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33890)

Creates a plain object from a SyncActionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncActionMessage`](SyncActionMessage.md)

SyncActionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33875](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33875)

Verifies a SyncActionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
