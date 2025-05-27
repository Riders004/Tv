# Class: IdentityKeyPairStructure

Defined in: [WAProto/index.d.ts:8172](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8172)

Represents an IdentityKeyPairStructure.

## Implements

- [`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

## Constructors

### new IdentityKeyPairStructure()

> **new IdentityKeyPairStructure**(`properties`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:8178](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8178)

Constructs a new IdentityKeyPairStructure.

#### Parameters

##### properties?

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

Properties to set

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

## Properties

### privateKey

> **privateKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:8184](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8184)

IdentityKeyPairStructure privateKey.

#### Implementation of

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md).[`privateKey`](../interfaces/IIdentityKeyPairStructure.md#privatekey)

***

### publicKey

> **publicKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:8181](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8181)

IdentityKeyPairStructure publicKey.

#### Implementation of

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md).[`publicKey`](../interfaces/IIdentityKeyPairStructure.md#publickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8254)

Converts this IdentityKeyPairStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:8191](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8191)

Creates a new IdentityKeyPairStructure instance using the specified properties.

#### Parameters

##### properties?

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

Properties to set

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:8217](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8217)

Decodes an IdentityKeyPairStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:8226](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8226)

Decodes an IdentityKeyPairStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8199](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8199)

Encodes the specified IdentityKeyPairStructure message. Does not implicitly [verify](IdentityKeyPairStructure.md#verify) messages.

#### Parameters

##### message

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

IdentityKeyPairStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8207](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8207)

Encodes the specified IdentityKeyPairStructure message, length delimited. Does not implicitly [verify](IdentityKeyPairStructure.md#verify) messages.

#### Parameters

##### message

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

IdentityKeyPairStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:8240](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8240)

Creates an IdentityKeyPairStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8248](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8248)

Creates a plain object from an IdentityKeyPairStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8233](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8233)

Verifies an IdentityKeyPairStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
