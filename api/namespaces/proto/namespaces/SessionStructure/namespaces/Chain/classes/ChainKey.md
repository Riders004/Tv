# Class: ChainKey

Defined in: [WAProto/index.d.ts:28506](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28506)

Represents a ChainKey.

## Implements

- [`IChainKey`](../interfaces/IChainKey.md)

## Constructors

### new ChainKey()

> **new ChainKey**(`properties`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:28512](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28512)

Constructs a new ChainKey.

#### Parameters

##### properties?

[`IChainKey`](../interfaces/IChainKey.md)

Properties to set

#### Returns

[`ChainKey`](ChainKey.md)

## Properties

### index

> **index**: `number`

Defined in: [WAProto/index.d.ts:28515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28515)

ChainKey index.

#### Implementation of

[`IChainKey`](../interfaces/IChainKey.md).[`index`](../interfaces/IChainKey.md#index)

***

### key

> **key**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28518)

ChainKey key.

#### Implementation of

[`IChainKey`](../interfaces/IChainKey.md).[`key`](../interfaces/IChainKey.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28588](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28588)

Converts this ChainKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:28525](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28525)

Creates a new ChainKey instance using the specified properties.

#### Parameters

##### properties?

[`IChainKey`](../interfaces/IChainKey.md)

Properties to set

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:28551](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28551)

Decodes a ChainKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:28560](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28560)

Decodes a ChainKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28533](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28533)

Encodes the specified ChainKey message. Does not implicitly [verify](ChainKey.md#verify) messages.

#### Parameters

##### message

[`IChainKey`](../interfaces/IChainKey.md)

ChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28541)

Encodes the specified ChainKey message, length delimited. Does not implicitly [verify](ChainKey.md#verify) messages.

#### Parameters

##### message

[`IChainKey`](../interfaces/IChainKey.md)

ChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:28574](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28574)

Creates a ChainKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28582](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28582)

Creates a plain object from a ChainKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`ChainKey`](ChainKey.md)

ChainKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28567)

Verifies a ChainKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
