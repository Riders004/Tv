# Class: SenderKeyStateStructure

Defined in: [WAProto/index.d.ts:27749](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27749)

Represents a SenderKeyStateStructure.

## Implements

- [`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

## Constructors

### new SenderKeyStateStructure()

> **new SenderKeyStateStructure**(`properties`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:27755](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27755)

Constructs a new SenderKeyStateStructure.

#### Parameters

##### properties?

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

Properties to set

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

## Properties

### senderChainKey?

> `optional` **senderChainKey**: `null` \| [`ISenderChainKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderChainKey.md)

Defined in: [WAProto/index.d.ts:27761](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27761)

SenderKeyStateStructure senderChainKey.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderChainKey`](../interfaces/ISenderKeyStateStructure.md#senderchainkey)

***

### senderKeyId

> **senderKeyId**: `number`

Defined in: [WAProto/index.d.ts:27758](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27758)

SenderKeyStateStructure senderKeyId.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderKeyId`](../interfaces/ISenderKeyStateStructure.md#senderkeyid)

***

### senderMessageKeys

> **senderMessageKeys**: [`ISenderMessageKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderMessageKey.md)[]

Defined in: [WAProto/index.d.ts:27767](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27767)

SenderKeyStateStructure senderMessageKeys.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderMessageKeys`](../interfaces/ISenderKeyStateStructure.md#sendermessagekeys)

***

### senderSigningKey?

> `optional` **senderSigningKey**: `null` \| [`ISenderSigningKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderSigningKey.md)

Defined in: [WAProto/index.d.ts:27764](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27764)

SenderKeyStateStructure senderSigningKey.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderSigningKey`](../interfaces/ISenderKeyStateStructure.md#sendersigningkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27837](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27837)

Converts this SenderKeyStateStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:27774](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27774)

Creates a new SenderKeyStateStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

Properties to set

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:27800](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27800)

Decodes a SenderKeyStateStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:27809](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27809)

Decodes a SenderKeyStateStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27782](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27782)

Encodes the specified SenderKeyStateStructure message. Does not implicitly [verify](SenderKeyStateStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

SenderKeyStateStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27790](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27790)

Encodes the specified SenderKeyStateStructure message, length delimited. Does not implicitly [verify](SenderKeyStateStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

SenderKeyStateStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:27823](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27823)

Creates a SenderKeyStateStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27831](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27831)

Creates a plain object from a SenderKeyStateStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27816](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27816)

Verifies a SenderKeyStateStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
