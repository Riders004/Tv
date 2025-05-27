# Class: ADVSignedKeyIndexList

Defined in: [WAProto/index.d.ts:463](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L463)

Represents a ADVSignedKeyIndexList.

## Implements

- [`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

## Constructors

### new ADVSignedKeyIndexList()

> **new ADVSignedKeyIndexList**(`properties`?): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:469](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L469)

Constructs a new ADVSignedKeyIndexList.

#### Parameters

##### properties?

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

Properties to set

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

## Properties

### accountSignature

> **accountSignature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:475](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L475)

ADVSignedKeyIndexList accountSignature.

#### Implementation of

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md).[`accountSignature`](../interfaces/IADVSignedKeyIndexList.md#accountsignature)

***

### accountSignatureKey

> **accountSignatureKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:478](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L478)

ADVSignedKeyIndexList accountSignatureKey.

#### Implementation of

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md).[`accountSignatureKey`](../interfaces/IADVSignedKeyIndexList.md#accountsignaturekey)

***

### details

> **details**: `Uint8Array`

Defined in: [WAProto/index.d.ts:472](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L472)

ADVSignedKeyIndexList details.

#### Implementation of

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md).[`details`](../interfaces/IADVSignedKeyIndexList.md#details)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:548](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L548)

Converts this ADVSignedKeyIndexList to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:485](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L485)

Creates a new ADVSignedKeyIndexList instance using the specified properties.

#### Parameters

##### properties?

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

Properties to set

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

ADVSignedKeyIndexList instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:511](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L511)

Decodes a ADVSignedKeyIndexList message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

ADVSignedKeyIndexList

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:520](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L520)

Decodes a ADVSignedKeyIndexList message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

ADVSignedKeyIndexList

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:493](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L493)

Encodes the specified ADVSignedKeyIndexList message. Does not implicitly [verify](ADVSignedKeyIndexList.md#verify) messages.

#### Parameters

##### message

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

ADVSignedKeyIndexList message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:501](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L501)

Encodes the specified ADVSignedKeyIndexList message, length delimited. Does not implicitly [verify](ADVSignedKeyIndexList.md#verify) messages.

#### Parameters

##### message

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

ADVSignedKeyIndexList message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:534](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L534)

Creates a ADVSignedKeyIndexList message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

ADVSignedKeyIndexList

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:542](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L542)

Creates a plain object from a ADVSignedKeyIndexList message. Also converts values to other types if specified.

#### Parameters

##### message

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

ADVSignedKeyIndexList

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:527](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L527)

Verifies a ADVSignedKeyIndexList message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
