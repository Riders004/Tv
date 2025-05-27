# Class: MessageKey

Defined in: [WAProto/index.d.ts:28608](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28608)

Represents a MessageKey.

## Implements

- [`IMessageKey`](../interfaces/IMessageKey.md)

## Constructors

### new MessageKey()

> **new MessageKey**(`properties`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:28614](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28614)

Constructs a new MessageKey.

#### Parameters

##### properties?

[`IMessageKey`](../interfaces/IMessageKey.md)

Properties to set

#### Returns

[`MessageKey`](MessageKey.md)

## Properties

### cipherKey

> **cipherKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28620](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28620)

MessageKey cipherKey.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`cipherKey`](../interfaces/IMessageKey.md#cipherkey)

***

### index

> **index**: `number`

Defined in: [WAProto/index.d.ts:28617](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28617)

MessageKey index.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`index`](../interfaces/IMessageKey.md#index)

***

### iv

> **iv**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28626](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28626)

MessageKey iv.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`iv`](../interfaces/IMessageKey.md#iv)

***

### macKey

> **macKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28623](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28623)

MessageKey macKey.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`macKey`](../interfaces/IMessageKey.md#mackey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28696](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28696)

Converts this MessageKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:28633](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28633)

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

Defined in: [WAProto/index.d.ts:28659](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28659)

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

Defined in: [WAProto/index.d.ts:28668](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28668)

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

Defined in: [WAProto/index.d.ts:28641](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28641)

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

Defined in: [WAProto/index.d.ts:28649](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28649)

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

Defined in: [WAProto/index.d.ts:28682](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28682)

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

Defined in: [WAProto/index.d.ts:28690](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28690)

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

Defined in: [WAProto/index.d.ts:28675](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28675)

Verifies a MessageKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
