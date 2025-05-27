# Class: ADVSignedDeviceIdentity

Defined in: [WAProto/index.d.ts:256](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L256)

Represents a ADVSignedDeviceIdentity.

## Implements

- [`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

## Constructors

### new ADVSignedDeviceIdentity()

> **new ADVSignedDeviceIdentity**(`properties`?): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L262)

Constructs a new ADVSignedDeviceIdentity.

#### Parameters

##### properties?

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

Properties to set

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

## Properties

### accountSignature

> **accountSignature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:271](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L271)

ADVSignedDeviceIdentity accountSignature.

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`accountSignature`](../interfaces/IADVSignedDeviceIdentity.md#accountsignature)

***

### accountSignatureKey

> **accountSignatureKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:268](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L268)

ADVSignedDeviceIdentity accountSignatureKey.

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`accountSignatureKey`](../interfaces/IADVSignedDeviceIdentity.md#accountsignaturekey)

***

### details

> **details**: `Uint8Array`

Defined in: [WAProto/index.d.ts:265](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L265)

ADVSignedDeviceIdentity details.

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`details`](../interfaces/IADVSignedDeviceIdentity.md#details)

***

### deviceSignature

> **deviceSignature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:274](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L274)

ADVSignedDeviceIdentity deviceSignature.

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`deviceSignature`](../interfaces/IADVSignedDeviceIdentity.md#devicesignature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:344](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L344)

Converts this ADVSignedDeviceIdentity to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:281](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L281)

Creates a new ADVSignedDeviceIdentity instance using the specified properties.

#### Parameters

##### properties?

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

Properties to set

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

ADVSignedDeviceIdentity instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:307](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L307)

Decodes a ADVSignedDeviceIdentity message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

ADVSignedDeviceIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:316](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L316)

Decodes a ADVSignedDeviceIdentity message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

ADVSignedDeviceIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:289](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L289)

Encodes the specified ADVSignedDeviceIdentity message. Does not implicitly [verify](ADVSignedDeviceIdentity.md#verify) messages.

#### Parameters

##### message

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

ADVSignedDeviceIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:297](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L297)

Encodes the specified ADVSignedDeviceIdentity message, length delimited. Does not implicitly [verify](ADVSignedDeviceIdentity.md#verify) messages.

#### Parameters

##### message

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

ADVSignedDeviceIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:330](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L330)

Creates a ADVSignedDeviceIdentity message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

ADVSignedDeviceIdentity

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:338](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L338)

Creates a plain object from a ADVSignedDeviceIdentity message. Also converts values to other types if specified.

#### Parameters

##### message

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

ADVSignedDeviceIdentity

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:323](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L323)

Verifies a ADVSignedDeviceIdentity message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
