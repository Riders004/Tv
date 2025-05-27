# Class: SyncdRecord

Defined in: [WAProto/index.d.ts:34709](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34709)

Represents a SyncdRecord.

## Implements

- [`ISyncdRecord`](../interfaces/ISyncdRecord.md)

## Constructors

### new SyncdRecord()

> **new SyncdRecord**(`properties`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:34715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34715)

Constructs a new SyncdRecord.

#### Parameters

##### properties?

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

Properties to set

#### Returns

[`SyncdRecord`](SyncdRecord.md)

## Properties

### index?

> `optional` **index**: `null` \| [`ISyncdIndex`](../interfaces/ISyncdIndex.md)

Defined in: [WAProto/index.d.ts:34718](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34718)

SyncdRecord index.

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`index`](../interfaces/ISyncdRecord.md#index)

***

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:34724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34724)

SyncdRecord keyId.

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`keyId`](../interfaces/ISyncdRecord.md#keyid)

***

### value?

> `optional` **value**: `null` \| [`ISyncdValue`](../interfaces/ISyncdValue.md)

Defined in: [WAProto/index.d.ts:34721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34721)

SyncdRecord value.

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`value`](../interfaces/ISyncdRecord.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34794)

Converts this SyncdRecord to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:34731](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34731)

Creates a new SyncdRecord instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

Properties to set

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:34757](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34757)

Decodes a SyncdRecord message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:34766](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34766)

Decodes a SyncdRecord message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34739)

Encodes the specified SyncdRecord message. Does not implicitly [verify](SyncdRecord.md#verify) messages.

#### Parameters

##### message

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

SyncdRecord message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34747](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34747)

Encodes the specified SyncdRecord message, length delimited. Does not implicitly [verify](SyncdRecord.md#verify) messages.

#### Parameters

##### message

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

SyncdRecord message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:34780](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34780)

Creates a SyncdRecord message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34788](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34788)

Creates a plain object from a SyncdRecord message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34773](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34773)

Verifies a SyncdRecord message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
