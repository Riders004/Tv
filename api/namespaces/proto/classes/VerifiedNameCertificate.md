# Class: VerifiedNameCertificate

Defined in: [WAProto/index.d.ts:35621](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35621)

Represents a VerifiedNameCertificate.

## Implements

- [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

## Constructors

### new VerifiedNameCertificate()

> **new VerifiedNameCertificate**(`properties`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:35627](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35627)

Constructs a new VerifiedNameCertificate.

#### Parameters

##### properties?

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Properties to set

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

## Properties

### details

> **details**: `Uint8Array`

Defined in: [WAProto/index.d.ts:35630](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35630)

VerifiedNameCertificate details.

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`details`](../interfaces/IVerifiedNameCertificate.md#details)

***

### serverSignature

> **serverSignature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:35636](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35636)

VerifiedNameCertificate serverSignature.

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`serverSignature`](../interfaces/IVerifiedNameCertificate.md#serversignature)

***

### signature

> **signature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:35633](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35633)

VerifiedNameCertificate signature.

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`signature`](../interfaces/IVerifiedNameCertificate.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35706](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35706)

Converts this VerifiedNameCertificate to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:35643](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35643)

Creates a new VerifiedNameCertificate instance using the specified properties.

#### Parameters

##### properties?

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Properties to set

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:35669](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35669)

Decodes a VerifiedNameCertificate message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:35678](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35678)

Decodes a VerifiedNameCertificate message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35651](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35651)

Encodes the specified VerifiedNameCertificate message. Does not implicitly [verify](VerifiedNameCertificate.md#verify) messages.

#### Parameters

##### message

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

VerifiedNameCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35659](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35659)

Encodes the specified VerifiedNameCertificate message, length delimited. Does not implicitly [verify](VerifiedNameCertificate.md#verify) messages.

#### Parameters

##### message

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

VerifiedNameCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:35692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35692)

Creates a VerifiedNameCertificate message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35700](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35700)

Creates a plain object from a VerifiedNameCertificate message. Also converts values to other types if specified.

#### Parameters

##### message

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35685](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35685)

Verifies a VerifiedNameCertificate message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
