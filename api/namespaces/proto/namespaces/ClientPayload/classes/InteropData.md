# Class: InteropData

Defined in: [WAProto/index.d.ts:3335](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3335)

Represents an InteropData.

## Implements

- [`IInteropData`](../interfaces/IInteropData.md)

## Constructors

### new InteropData()

> **new InteropData**(`properties`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:3341](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3341)

Constructs a new InteropData.

#### Parameters

##### properties?

[`IInteropData`](../interfaces/IInteropData.md)

Properties to set

#### Returns

[`InteropData`](InteropData.md)

## Properties

### accountId

> **accountId**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:3344](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3344)

InteropData accountId.

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`accountId`](../interfaces/IInteropData.md#accountid)

***

### token

> **token**: `Uint8Array`

Defined in: [WAProto/index.d.ts:3347](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3347)

InteropData token.

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`token`](../interfaces/IInteropData.md#token)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3417](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3417)

Converts this InteropData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:3354](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3354)

Creates a new InteropData instance using the specified properties.

#### Parameters

##### properties?

[`IInteropData`](../interfaces/IInteropData.md)

Properties to set

#### Returns

[`InteropData`](InteropData.md)

InteropData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:3380](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3380)

Decodes an InteropData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InteropData`](InteropData.md)

InteropData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:3389](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3389)

Decodes an InteropData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InteropData`](InteropData.md)

InteropData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3362](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3362)

Encodes the specified InteropData message. Does not implicitly [verify](InteropData.md#verify) messages.

#### Parameters

##### message

[`IInteropData`](../interfaces/IInteropData.md)

InteropData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3370](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3370)

Encodes the specified InteropData message, length delimited. Does not implicitly [verify](InteropData.md#verify) messages.

#### Parameters

##### message

[`IInteropData`](../interfaces/IInteropData.md)

InteropData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:3403](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3403)

Creates an InteropData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InteropData`](InteropData.md)

InteropData

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:3411](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3411)

Creates a plain object from an InteropData message. Also converts values to other types if specified.

#### Parameters

##### message

[`InteropData`](InteropData.md)

InteropData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3396](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3396)

Verifies an InteropData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
