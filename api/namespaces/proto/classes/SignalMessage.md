# Class: SignalMessage

Defined in: [WAProto/index.d.ts:28946](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28946)

Represents a SignalMessage.

## Implements

- [`ISignalMessage`](../interfaces/ISignalMessage.md)

## Constructors

### new SignalMessage()

> **new SignalMessage**(`properties`?): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:28952](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28952)

Constructs a new SignalMessage.

#### Parameters

##### properties?

[`ISignalMessage`](../interfaces/ISignalMessage.md)

Properties to set

#### Returns

[`SignalMessage`](SignalMessage.md)

## Properties

### ciphertext

> **ciphertext**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28964](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28964)

SignalMessage ciphertext.

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`ciphertext`](../interfaces/ISignalMessage.md#ciphertext)

***

### counter

> **counter**: `number`

Defined in: [WAProto/index.d.ts:28958](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28958)

SignalMessage counter.

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`counter`](../interfaces/ISignalMessage.md#counter)

***

### previousCounter

> **previousCounter**: `number`

Defined in: [WAProto/index.d.ts:28961](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28961)

SignalMessage previousCounter.

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`previousCounter`](../interfaces/ISignalMessage.md#previouscounter)

***

### ratchetKey

> **ratchetKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28955](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28955)

SignalMessage ratchetKey.

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`ratchetKey`](../interfaces/ISignalMessage.md#ratchetkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29034](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29034)

Converts this SignalMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:28971](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28971)

Creates a new SignalMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISignalMessage`](../interfaces/ISignalMessage.md)

Properties to set

#### Returns

[`SignalMessage`](SignalMessage.md)

SignalMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:28997](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28997)

Decodes a SignalMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SignalMessage`](SignalMessage.md)

SignalMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:29006](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29006)

Decodes a SignalMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SignalMessage`](SignalMessage.md)

SignalMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28979](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28979)

Encodes the specified SignalMessage message. Does not implicitly [verify](SignalMessage.md#verify) messages.

#### Parameters

##### message

[`ISignalMessage`](../interfaces/ISignalMessage.md)

SignalMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28987](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28987)

Encodes the specified SignalMessage message, length delimited. Does not implicitly [verify](SignalMessage.md#verify) messages.

#### Parameters

##### message

[`ISignalMessage`](../interfaces/ISignalMessage.md)

SignalMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:29020](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29020)

Creates a SignalMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SignalMessage`](SignalMessage.md)

SignalMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:29028](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29028)

Creates a plain object from a SignalMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SignalMessage`](SignalMessage.md)

SignalMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29013](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29013)

Verifies a SignalMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
