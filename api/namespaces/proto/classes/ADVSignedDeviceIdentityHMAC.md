# Class: ADVSignedDeviceIdentityHMAC

Defined in: [WAProto/index.d.ts:361](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L361)

Represents a ADVSignedDeviceIdentityHMAC.

## Implements

- [`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

## Constructors

### new ADVSignedDeviceIdentityHMAC()

> **new ADVSignedDeviceIdentityHMAC**(`properties`?): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:367](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L367)

Constructs a new ADVSignedDeviceIdentityHMAC.

#### Parameters

##### properties?

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

Properties to set

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

## Properties

### accountType

> **accountType**: [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:376](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L376)

ADVSignedDeviceIdentityHMAC accountType.

#### Implementation of

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md).[`accountType`](../interfaces/IADVSignedDeviceIdentityHMAC.md#accounttype)

***

### details

> **details**: `Uint8Array`

Defined in: [WAProto/index.d.ts:370](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L370)

ADVSignedDeviceIdentityHMAC details.

#### Implementation of

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md).[`details`](../interfaces/IADVSignedDeviceIdentityHMAC.md#details)

***

### hmac

> **hmac**: `Uint8Array`

Defined in: [WAProto/index.d.ts:373](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L373)

ADVSignedDeviceIdentityHMAC hmac.

#### Implementation of

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md).[`hmac`](../interfaces/IADVSignedDeviceIdentityHMAC.md#hmac)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:446](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L446)

Converts this ADVSignedDeviceIdentityHMAC to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:383](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L383)

Creates a new ADVSignedDeviceIdentityHMAC instance using the specified properties.

#### Parameters

##### properties?

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

Properties to set

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

ADVSignedDeviceIdentityHMAC instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:409](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L409)

Decodes a ADVSignedDeviceIdentityHMAC message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

ADVSignedDeviceIdentityHMAC

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:418](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L418)

Decodes a ADVSignedDeviceIdentityHMAC message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

ADVSignedDeviceIdentityHMAC

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:391](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L391)

Encodes the specified ADVSignedDeviceIdentityHMAC message. Does not implicitly [verify](ADVSignedDeviceIdentityHMAC.md#verify) messages.

#### Parameters

##### message

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

ADVSignedDeviceIdentityHMAC message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:399](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L399)

Encodes the specified ADVSignedDeviceIdentityHMAC message, length delimited. Does not implicitly [verify](ADVSignedDeviceIdentityHMAC.md#verify) messages.

#### Parameters

##### message

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

ADVSignedDeviceIdentityHMAC message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:432](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L432)

Creates a ADVSignedDeviceIdentityHMAC message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

ADVSignedDeviceIdentityHMAC

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:440](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L440)

Creates a plain object from a ADVSignedDeviceIdentityHMAC message. Also converts values to other types if specified.

#### Parameters

##### message

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

ADVSignedDeviceIdentityHMAC

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:425](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L425)

Verifies a ADVSignedDeviceIdentityHMAC message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
