# Class: KeepInChat

Defined in: [WAProto/index.d.ts:8391](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8391)

Represents a KeepInChat.

## Implements

- [`IKeepInChat`](../interfaces/IKeepInChat.md)

## Constructors

### new KeepInChat()

> **new KeepInChat**(`properties`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:8397](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8397)

Constructs a new KeepInChat.

#### Parameters

##### properties?

[`IKeepInChat`](../interfaces/IKeepInChat.md)

Properties to set

#### Returns

[`KeepInChat`](KeepInChat.md)

## Properties

### clientTimestampMs

> **clientTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:8412](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8412)

KeepInChat clientTimestampMs.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`clientTimestampMs`](../interfaces/IKeepInChat.md#clienttimestampms)

***

### deviceJid

> **deviceJid**: `string`

Defined in: [WAProto/index.d.ts:8409](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8409)

KeepInChat deviceJid.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`deviceJid`](../interfaces/IKeepInChat.md#devicejid)

***

### keepType

> **keepType**: [`KeepType`](../enumerations/KeepType.md)

Defined in: [WAProto/index.d.ts:8400](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8400)

KeepInChat keepType.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`keepType`](../interfaces/IKeepInChat.md#keeptype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8406](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8406)

KeepInChat key.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`key`](../interfaces/IKeepInChat.md#key)

***

### serverTimestamp

> **serverTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:8403](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8403)

KeepInChat serverTimestamp.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`serverTimestamp`](../interfaces/IKeepInChat.md#servertimestamp)

***

### serverTimestampMs

> **serverTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:8415](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8415)

KeepInChat serverTimestampMs.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`serverTimestampMs`](../interfaces/IKeepInChat.md#servertimestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8485](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8485)

Converts this KeepInChat to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:8422](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8422)

Creates a new KeepInChat instance using the specified properties.

#### Parameters

##### properties?

[`IKeepInChat`](../interfaces/IKeepInChat.md)

Properties to set

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:8448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8448)

Decodes a KeepInChat message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:8457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8457)

Decodes a KeepInChat message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8430](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8430)

Encodes the specified KeepInChat message. Does not implicitly [verify](KeepInChat.md#verify) messages.

#### Parameters

##### message

[`IKeepInChat`](../interfaces/IKeepInChat.md)

KeepInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8438](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8438)

Encodes the specified KeepInChat message, length delimited. Does not implicitly [verify](KeepInChat.md#verify) messages.

#### Parameters

##### message

[`IKeepInChat`](../interfaces/IKeepInChat.md)

KeepInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:8471](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8471)

Creates a KeepInChat message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8479](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8479)

Creates a plain object from a KeepInChat message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeepInChat`](KeepInChat.md)

KeepInChat

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8464](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8464)

Verifies a KeepInChat message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
