# Class: CertChain

Defined in: [WAProto/index.d.ts:2014](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2014)

Represents a CertChain.

## Implements

- [`ICertChain`](../interfaces/ICertChain.md)

## Constructors

### new CertChain()

> **new CertChain**(`properties`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2020](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2020)

Constructs a new CertChain.

#### Parameters

##### properties?

[`ICertChain`](../interfaces/ICertChain.md)

Properties to set

#### Returns

[`CertChain`](CertChain.md)

## Properties

### intermediate?

> `optional` **intermediate**: `null` \| [`INoiseCertificate`](../namespaces/CertChain/interfaces/INoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2026](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2026)

CertChain intermediate.

#### Implementation of

[`ICertChain`](../interfaces/ICertChain.md).[`intermediate`](../interfaces/ICertChain.md#intermediate)

***

### leaf?

> `optional` **leaf**: `null` \| [`INoiseCertificate`](../namespaces/CertChain/interfaces/INoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2023](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2023)

CertChain leaf.

#### Implementation of

[`ICertChain`](../interfaces/ICertChain.md).[`leaf`](../interfaces/ICertChain.md#leaf)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2096](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2096)

Converts this CertChain to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2033](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2033)

Creates a new CertChain instance using the specified properties.

#### Parameters

##### properties?

[`ICertChain`](../interfaces/ICertChain.md)

Properties to set

#### Returns

[`CertChain`](CertChain.md)

CertChain instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2059](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2059)

Decodes a CertChain message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CertChain`](CertChain.md)

CertChain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2068](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2068)

Decodes a CertChain message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CertChain`](CertChain.md)

CertChain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2041](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2041)

Encodes the specified CertChain message. Does not implicitly [verify](CertChain.md#verify) messages.

#### Parameters

##### message

[`ICertChain`](../interfaces/ICertChain.md)

CertChain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2049](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2049)

Encodes the specified CertChain message, length delimited. Does not implicitly [verify](CertChain.md#verify) messages.

#### Parameters

##### message

[`ICertChain`](../interfaces/ICertChain.md)

CertChain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2082](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2082)

Creates a CertChain message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CertChain`](CertChain.md)

CertChain

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:2090](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2090)

Creates a plain object from a CertChain message. Also converts values to other types if specified.

#### Parameters

##### message

[`CertChain`](CertChain.md)

CertChain

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2075](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2075)

Verifies a CertChain message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
