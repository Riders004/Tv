# Class: MessageKey

Defined in: [WAProto/index.d.ts:23435](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23435)

Represents a MessageKey.

## Implements

- [`IMessageKey`](../interfaces/IMessageKey.md)

## Constructors

### new MessageKey()

> **new MessageKey**(`properties`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:23441](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23441)

Constructs a new MessageKey.

#### Parameters

##### properties?

[`IMessageKey`](../interfaces/IMessageKey.md)

Properties to set

#### Returns

[`MessageKey`](MessageKey.md)

## Properties

### fromMe

> **fromMe**: `boolean`

Defined in: [WAProto/index.d.ts:23447](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23447)

MessageKey fromMe.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`fromMe`](../interfaces/IMessageKey.md#fromme)

***

### id

> **id**: `string`

Defined in: [WAProto/index.d.ts:23450](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23450)

MessageKey id.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`id`](../interfaces/IMessageKey.md#id)

***

### participant

> **participant**: `string`

Defined in: [WAProto/index.d.ts:23453](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23453)

MessageKey participant.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`participant`](../interfaces/IMessageKey.md#participant)

***

### remoteJid

> **remoteJid**: `string`

Defined in: [WAProto/index.d.ts:23444](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23444)

MessageKey remoteJid.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`remoteJid`](../interfaces/IMessageKey.md#remotejid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23523](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23523)

Converts this MessageKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:23460](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23460)

Creates a new MessageKey instance using the specified properties.

#### Parameters

##### properties?

[`IMessageKey`](../interfaces/IMessageKey.md)

Properties to set

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:23486](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23486)

Decodes a MessageKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:23495](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23495)

Decodes a MessageKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23468](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23468)

Encodes the specified MessageKey message. Does not implicitly [verify](MessageKey.md#verify) messages.

#### Parameters

##### message

[`IMessageKey`](../interfaces/IMessageKey.md)

MessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23476](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23476)

Encodes the specified MessageKey message, length delimited. Does not implicitly [verify](MessageKey.md#verify) messages.

#### Parameters

##### message

[`IMessageKey`](../interfaces/IMessageKey.md)

MessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:23509](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23509)

Creates a MessageKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:23517](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23517)

Creates a plain object from a MessageKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageKey`](MessageKey.md)

MessageKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23502](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23502)

Verifies a MessageKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
