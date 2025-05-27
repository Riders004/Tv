# Class: KeyExchangeMessage

Defined in: [WAProto/index.d.ts:8515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8515)

Represents a KeyExchangeMessage.

## Implements

- [`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

## Constructors

### new KeyExchangeMessage()

> **new KeyExchangeMessage**(`properties`?): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:8521](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8521)

Constructs a new KeyExchangeMessage.

#### Parameters

##### properties?

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

Properties to set

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

## Properties

### baseKey

> **baseKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:8527](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8527)

KeyExchangeMessage baseKey.

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`baseKey`](../interfaces/IKeyExchangeMessage.md#basekey)

***

### baseKeySignature

> **baseKeySignature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:8536](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8536)

KeyExchangeMessage baseKeySignature.

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`baseKeySignature`](../interfaces/IKeyExchangeMessage.md#basekeysignature)

***

### id

> **id**: `number`

Defined in: [WAProto/index.d.ts:8524](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8524)

KeyExchangeMessage id.

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`id`](../interfaces/IKeyExchangeMessage.md#id)

***

### identityKey

> **identityKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:8533](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8533)

KeyExchangeMessage identityKey.

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`identityKey`](../interfaces/IKeyExchangeMessage.md#identitykey)

***

### ratchetKey

> **ratchetKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:8530](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8530)

KeyExchangeMessage ratchetKey.

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`ratchetKey`](../interfaces/IKeyExchangeMessage.md#ratchetkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8606](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8606)

Converts this KeyExchangeMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:8543](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8543)

Creates a new KeyExchangeMessage instance using the specified properties.

#### Parameters

##### properties?

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

Properties to set

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

KeyExchangeMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:8569](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8569)

Decodes a KeyExchangeMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

KeyExchangeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:8578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8578)

Decodes a KeyExchangeMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

KeyExchangeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8551](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8551)

Encodes the specified KeyExchangeMessage message. Does not implicitly [verify](KeyExchangeMessage.md#verify) messages.

#### Parameters

##### message

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

KeyExchangeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8559](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8559)

Encodes the specified KeyExchangeMessage message, length delimited. Does not implicitly [verify](KeyExchangeMessage.md#verify) messages.

#### Parameters

##### message

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

KeyExchangeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:8592](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8592)

Creates a KeyExchangeMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

KeyExchangeMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8600](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8600)

Creates a plain object from a KeyExchangeMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeyExchangeMessage`](KeyExchangeMessage.md)

KeyExchangeMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8585](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8585)

Verifies a KeyExchangeMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
