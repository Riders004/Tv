# Class: ADVDeviceIdentity

Defined in: [WAProto/index.d.ts:25](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25)

Represents a ADVDeviceIdentity.

## Implements

- [`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

## Constructors

### new ADVDeviceIdentity()

> **new ADVDeviceIdentity**(`properties`?): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:31](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31)

Constructs a new ADVDeviceIdentity.

#### Parameters

##### properties?

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

Properties to set

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

## Properties

### accountType

> **accountType**: [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:43](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L43)

ADVDeviceIdentity accountType.

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`accountType`](../interfaces/IADVDeviceIdentity.md#accounttype)

***

### deviceType

> **deviceType**: [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:46](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L46)

ADVDeviceIdentity deviceType.

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`deviceType`](../interfaces/IADVDeviceIdentity.md#devicetype)

***

### keyIndex

> **keyIndex**: `number`

Defined in: [WAProto/index.d.ts:40](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L40)

ADVDeviceIdentity keyIndex.

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`keyIndex`](../interfaces/IADVDeviceIdentity.md#keyindex)

***

### rawId

> **rawId**: `number`

Defined in: [WAProto/index.d.ts:34](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34)

ADVDeviceIdentity rawId.

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`rawId`](../interfaces/IADVDeviceIdentity.md#rawid)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:37](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L37)

ADVDeviceIdentity timestamp.

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`timestamp`](../interfaces/IADVDeviceIdentity.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:116](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L116)

Converts this ADVDeviceIdentity to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:53](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L53)

Creates a new ADVDeviceIdentity instance using the specified properties.

#### Parameters

##### properties?

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

Properties to set

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

ADVDeviceIdentity instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:79](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L79)

Decodes a ADVDeviceIdentity message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

ADVDeviceIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:88](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L88)

Decodes a ADVDeviceIdentity message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

ADVDeviceIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:61](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L61)

Encodes the specified ADVDeviceIdentity message. Does not implicitly [verify](ADVDeviceIdentity.md#verify) messages.

#### Parameters

##### message

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

ADVDeviceIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:69](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L69)

Encodes the specified ADVDeviceIdentity message, length delimited. Does not implicitly [verify](ADVDeviceIdentity.md#verify) messages.

#### Parameters

##### message

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

ADVDeviceIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:102](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L102)

Creates a ADVDeviceIdentity message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

ADVDeviceIdentity

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:110](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L110)

Creates a plain object from a ADVDeviceIdentity message. Also converts values to other types if specified.

#### Parameters

##### message

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

ADVDeviceIdentity

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:95](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L95)

Verifies a ADVDeviceIdentity message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
