# Class: NoiseCertificate

Defined in: [WAProto/index.d.ts:24194](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24194)

Represents a NoiseCertificate.

## Implements

- [`INoiseCertificate`](../interfaces/INoiseCertificate.md)

## Constructors

### new NoiseCertificate()

> **new NoiseCertificate**(`properties`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:24200](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24200)

Constructs a new NoiseCertificate.

#### Parameters

##### properties?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

Properties to set

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

## Properties

### details

> **details**: `Uint8Array`

Defined in: [WAProto/index.d.ts:24203](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24203)

NoiseCertificate details.

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`details`](../interfaces/INoiseCertificate.md#details)

***

### signature

> **signature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:24206](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24206)

NoiseCertificate signature.

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`signature`](../interfaces/INoiseCertificate.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24276](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24276)

Converts this NoiseCertificate to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:24213](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24213)

Creates a new NoiseCertificate instance using the specified properties.

#### Parameters

##### properties?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

Properties to set

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:24239](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24239)

Decodes a NoiseCertificate message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:24248](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24248)

Decodes a NoiseCertificate message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24221)

Encodes the specified NoiseCertificate message. Does not implicitly [verify](NoiseCertificate.md#verify) messages.

#### Parameters

##### message

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

NoiseCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24229](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24229)

Encodes the specified NoiseCertificate message, length delimited. Does not implicitly [verify](NoiseCertificate.md#verify) messages.

#### Parameters

##### message

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

NoiseCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:24262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24262)

Creates a NoiseCertificate message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:24270](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24270)

Creates a plain object from a NoiseCertificate message. Also converts values to other types if specified.

#### Parameters

##### message

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24255](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24255)

Verifies a NoiseCertificate message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
