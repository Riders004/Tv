# Class: Chain

Defined in: [WAProto/index.d.ts:28402](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28402)

Represents a Chain.

## Implements

- [`IChain`](../interfaces/IChain.md)

## Constructors

### new Chain()

> **new Chain**(`properties`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:28408](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28408)

Constructs a new Chain.

#### Parameters

##### properties?

[`IChain`](../interfaces/IChain.md)

Properties to set

#### Returns

[`Chain`](Chain.md)

## Properties

### chainKey?

> `optional` **chainKey**: `null` \| [`IChainKey`](../namespaces/Chain/interfaces/IChainKey.md)

Defined in: [WAProto/index.d.ts:28417](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28417)

Chain chainKey.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`chainKey`](../interfaces/IChain.md#chainkey)

***

### messageKeys

> **messageKeys**: [`IMessageKey`](../namespaces/Chain/interfaces/IMessageKey.md)[]

Defined in: [WAProto/index.d.ts:28420](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28420)

Chain messageKeys.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`messageKeys`](../interfaces/IChain.md#messagekeys)

***

### senderRatchetKey

> **senderRatchetKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28411](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28411)

Chain senderRatchetKey.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`senderRatchetKey`](../interfaces/IChain.md#senderratchetkey)

***

### senderRatchetKeyPrivate

> **senderRatchetKeyPrivate**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28414](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28414)

Chain senderRatchetKeyPrivate.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`senderRatchetKeyPrivate`](../interfaces/IChain.md#senderratchetkeyprivate)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28490](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28490)

Converts this Chain to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:28427](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28427)

Creates a new Chain instance using the specified properties.

#### Parameters

##### properties?

[`IChain`](../interfaces/IChain.md)

Properties to set

#### Returns

[`Chain`](Chain.md)

Chain instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:28453](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28453)

Decodes a Chain message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Chain`](Chain.md)

Chain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:28462](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28462)

Decodes a Chain message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Chain`](Chain.md)

Chain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28435](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28435)

Encodes the specified Chain message. Does not implicitly [verify](Chain.md#verify) messages.

#### Parameters

##### message

[`IChain`](../interfaces/IChain.md)

Chain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28443](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28443)

Encodes the specified Chain message, length delimited. Does not implicitly [verify](Chain.md#verify) messages.

#### Parameters

##### message

[`IChain`](../interfaces/IChain.md)

Chain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:28476](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28476)

Creates a Chain message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Chain`](Chain.md)

Chain

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28484](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28484)

Creates a plain object from a Chain message. Also converts values to other types if specified.

#### Parameters

##### message

[`Chain`](Chain.md)

Chain

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28469](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28469)

Verifies a Chain message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
