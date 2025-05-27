# Class: ScheduledCallEditMessage

Defined in: [WAProto/index.d.ts:21843](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21843)

Represents a ScheduledCallEditMessage.

## Implements

- [`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

## Constructors

### new ScheduledCallEditMessage()

> **new ScheduledCallEditMessage**(`properties`?): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:21849](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21849)

Constructs a new ScheduledCallEditMessage.

#### Parameters

##### properties?

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

Properties to set

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

## Properties

### editType

> **editType**: [`EditType`](../namespaces/ScheduledCallEditMessage/enumerations/EditType.md)

Defined in: [WAProto/index.d.ts:21855](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21855)

ScheduledCallEditMessage editType.

#### Implementation of

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md).[`editType`](../interfaces/IScheduledCallEditMessage.md#edittype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:21852](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21852)

ScheduledCallEditMessage key.

#### Implementation of

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md).[`key`](../interfaces/IScheduledCallEditMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21925](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21925)

Converts this ScheduledCallEditMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:21862](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21862)

Creates a new ScheduledCallEditMessage instance using the specified properties.

#### Parameters

##### properties?

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

Properties to set

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

ScheduledCallEditMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:21888](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21888)

Decodes a ScheduledCallEditMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

ScheduledCallEditMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:21897](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21897)

Decodes a ScheduledCallEditMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

ScheduledCallEditMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21870)

Encodes the specified ScheduledCallEditMessage message. Does not implicitly [verify](ScheduledCallEditMessage.md#verify) messages.

#### Parameters

##### message

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

ScheduledCallEditMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21878](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21878)

Encodes the specified ScheduledCallEditMessage message, length delimited. Does not implicitly [verify](ScheduledCallEditMessage.md#verify) messages.

#### Parameters

##### message

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

ScheduledCallEditMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:21911](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21911)

Creates a ScheduledCallEditMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

ScheduledCallEditMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21919)

Creates a plain object from a ScheduledCallEditMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

ScheduledCallEditMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21904](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21904)

Verifies a ScheduledCallEditMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
