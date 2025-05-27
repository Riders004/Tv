# Class: ServerHello

Defined in: [WAProto/index.d.ts:7364](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7364)

Represents a ServerHello.

## Implements

- [`IServerHello`](../interfaces/IServerHello.md)

## Constructors

### new ServerHello()

> **new ServerHello**(`properties`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:7370](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7370)

Constructs a new ServerHello.

#### Parameters

##### properties?

[`IServerHello`](../interfaces/IServerHello.md)

Properties to set

#### Returns

[`ServerHello`](ServerHello.md)

## Properties

### ephemeral

> **ephemeral**: `Uint8Array`

Defined in: [WAProto/index.d.ts:7373](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7373)

ServerHello ephemeral.

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`ephemeral`](../interfaces/IServerHello.md#ephemeral)

***

### payload

> **payload**: `Uint8Array`

Defined in: [WAProto/index.d.ts:7379](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7379)

ServerHello payload.

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`payload`](../interfaces/IServerHello.md#payload)

***

### static

> **static**: `Uint8Array`

Defined in: [WAProto/index.d.ts:7376](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7376)

ServerHello static.

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`static`](../interfaces/IServerHello.md#static)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7449](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7449)

Converts this ServerHello to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:7386](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7386)

Creates a new ServerHello instance using the specified properties.

#### Parameters

##### properties?

[`IServerHello`](../interfaces/IServerHello.md)

Properties to set

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:7412](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7412)

Decodes a ServerHello message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:7421](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7421)

Decodes a ServerHello message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7394](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7394)

Encodes the specified ServerHello message. Does not implicitly [verify](ServerHello.md#verify) messages.

#### Parameters

##### message

[`IServerHello`](../interfaces/IServerHello.md)

ServerHello message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7402](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7402)

Encodes the specified ServerHello message, length delimited. Does not implicitly [verify](ServerHello.md#verify) messages.

#### Parameters

##### message

[`IServerHello`](../interfaces/IServerHello.md)

ServerHello message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:7435](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7435)

Creates a ServerHello message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:7443](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7443)

Creates a plain object from a ServerHello message. Also converts values to other types if specified.

#### Parameters

##### message

[`ServerHello`](ServerHello.md)

ServerHello

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7428](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7428)

Verifies a ServerHello message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
