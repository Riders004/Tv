# Class: KeyId

Defined in: [WAProto/index.d.ts:8617](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8617)

Represents a KeyId.

## Implements

- [`IKeyId`](../interfaces/IKeyId.md)

## Constructors

### new KeyId()

> **new KeyId**(`properties`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:8623](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8623)

Constructs a new KeyId.

#### Parameters

##### properties?

[`IKeyId`](../interfaces/IKeyId.md)

Properties to set

#### Returns

[`KeyId`](KeyId.md)

## Properties

### id

> **id**: `Uint8Array`

Defined in: [WAProto/index.d.ts:8626](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8626)

KeyId id.

#### Implementation of

[`IKeyId`](../interfaces/IKeyId.md).[`id`](../interfaces/IKeyId.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8696](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8696)

Converts this KeyId to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:8633](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8633)

Creates a new KeyId instance using the specified properties.

#### Parameters

##### properties?

[`IKeyId`](../interfaces/IKeyId.md)

Properties to set

#### Returns

[`KeyId`](KeyId.md)

KeyId instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:8659](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8659)

Decodes a KeyId message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeyId`](KeyId.md)

KeyId

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:8668](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8668)

Decodes a KeyId message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeyId`](KeyId.md)

KeyId

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8641](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8641)

Encodes the specified KeyId message. Does not implicitly [verify](KeyId.md#verify) messages.

#### Parameters

##### message

[`IKeyId`](../interfaces/IKeyId.md)

KeyId message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8649](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8649)

Encodes the specified KeyId message, length delimited. Does not implicitly [verify](KeyId.md#verify) messages.

#### Parameters

##### message

[`IKeyId`](../interfaces/IKeyId.md)

KeyId message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:8682](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8682)

Creates a KeyId message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeyId`](KeyId.md)

KeyId

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8690](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8690)

Creates a plain object from a KeyId message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeyId`](KeyId.md)

KeyId

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8675](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8675)

Verifies a KeyId message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
