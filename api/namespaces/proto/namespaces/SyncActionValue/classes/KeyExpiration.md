# Class: KeyExpiration

Defined in: [WAProto/index.d.ts:31369](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31369)

Represents a KeyExpiration.

## Implements

- [`IKeyExpiration`](../interfaces/IKeyExpiration.md)

## Constructors

### new KeyExpiration()

> **new KeyExpiration**(`properties`?): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:31375](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31375)

Constructs a new KeyExpiration.

#### Parameters

##### properties?

[`IKeyExpiration`](../interfaces/IKeyExpiration.md)

Properties to set

#### Returns

[`KeyExpiration`](KeyExpiration.md)

## Properties

### expiredKeyEpoch

> **expiredKeyEpoch**: `number`

Defined in: [WAProto/index.d.ts:31378](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31378)

KeyExpiration expiredKeyEpoch.

#### Implementation of

[`IKeyExpiration`](../interfaces/IKeyExpiration.md).[`expiredKeyEpoch`](../interfaces/IKeyExpiration.md#expiredkeyepoch)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31448)

Converts this KeyExpiration to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:31385](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31385)

Creates a new KeyExpiration instance using the specified properties.

#### Parameters

##### properties?

[`IKeyExpiration`](../interfaces/IKeyExpiration.md)

Properties to set

#### Returns

[`KeyExpiration`](KeyExpiration.md)

KeyExpiration instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:31411](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31411)

Decodes a KeyExpiration message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeyExpiration`](KeyExpiration.md)

KeyExpiration

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:31420](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31420)

Decodes a KeyExpiration message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeyExpiration`](KeyExpiration.md)

KeyExpiration

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31393](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31393)

Encodes the specified KeyExpiration message. Does not implicitly [verify](KeyExpiration.md#verify) messages.

#### Parameters

##### message

[`IKeyExpiration`](../interfaces/IKeyExpiration.md)

KeyExpiration message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31401)

Encodes the specified KeyExpiration message, length delimited. Does not implicitly [verify](KeyExpiration.md#verify) messages.

#### Parameters

##### message

[`IKeyExpiration`](../interfaces/IKeyExpiration.md)

KeyExpiration message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:31434](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31434)

Creates a KeyExpiration message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeyExpiration`](KeyExpiration.md)

KeyExpiration

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31442](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31442)

Creates a plain object from a KeyExpiration message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeyExpiration`](KeyExpiration.md)

KeyExpiration

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31427](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31427)

Verifies a KeyExpiration message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
