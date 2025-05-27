# Class: ADVKeyIndexList

Defined in: [WAProto/index.d.ts:145](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L145)

Represents a ADVKeyIndexList.

## Implements

- [`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

## Constructors

### new ADVKeyIndexList()

> **new ADVKeyIndexList**(`properties`?): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:151](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L151)

Constructs a new ADVKeyIndexList.

#### Parameters

##### properties?

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

Properties to set

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

## Properties

### accountType

> **accountType**: [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:166](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L166)

ADVKeyIndexList accountType.

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`accountType`](../interfaces/IADVKeyIndexList.md#accounttype)

***

### currentIndex

> **currentIndex**: `number`

Defined in: [WAProto/index.d.ts:160](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L160)

ADVKeyIndexList currentIndex.

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`currentIndex`](../interfaces/IADVKeyIndexList.md#currentindex)

***

### rawId

> **rawId**: `number`

Defined in: [WAProto/index.d.ts:154](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L154)

ADVKeyIndexList rawId.

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`rawId`](../interfaces/IADVKeyIndexList.md#rawid)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L157)

ADVKeyIndexList timestamp.

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`timestamp`](../interfaces/IADVKeyIndexList.md#timestamp)

***

### validIndexes

> **validIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:163](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L163)

ADVKeyIndexList validIndexes.

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`validIndexes`](../interfaces/IADVKeyIndexList.md#validindexes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:236](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L236)

Converts this ADVKeyIndexList to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:173](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L173)

Creates a new ADVKeyIndexList instance using the specified properties.

#### Parameters

##### properties?

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

Properties to set

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

ADVKeyIndexList instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:199](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L199)

Decodes a ADVKeyIndexList message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

ADVKeyIndexList

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:208](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L208)

Decodes a ADVKeyIndexList message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

ADVKeyIndexList

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:181](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L181)

Encodes the specified ADVKeyIndexList message. Does not implicitly [verify](ADVKeyIndexList.md#verify) messages.

#### Parameters

##### message

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

ADVKeyIndexList message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:189](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L189)

Encodes the specified ADVKeyIndexList message, length delimited. Does not implicitly [verify](ADVKeyIndexList.md#verify) messages.

#### Parameters

##### message

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

ADVKeyIndexList message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:222](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L222)

Creates a ADVKeyIndexList message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

ADVKeyIndexList

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:230](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L230)

Creates a plain object from a ADVKeyIndexList message. Also converts values to other types if specified.

#### Parameters

##### message

[`ADVKeyIndexList`](ADVKeyIndexList.md)

ADVKeyIndexList

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:215](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L215)

Verifies a ADVKeyIndexList message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
