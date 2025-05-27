# Class: QP

Defined in: [WAProto/index.d.ts:26628](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26628)

Represents a QP.

## Implements

- [`IQP`](../interfaces/IQP.md)

## Constructors

### new QP()

> **new QP**(`properties`?): [`QP`](QP.md)

Defined in: [WAProto/index.d.ts:26634](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26634)

Constructs a new QP.

#### Parameters

##### properties?

[`IQP`](../interfaces/IQP.md)

Properties to set

#### Returns

[`QP`](QP.md)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26704](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26704)

Converts this QP to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`QP`](QP.md)

Defined in: [WAProto/index.d.ts:26641](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26641)

Creates a new QP instance using the specified properties.

#### Parameters

##### properties?

[`IQP`](../interfaces/IQP.md)

Properties to set

#### Returns

[`QP`](QP.md)

QP instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`QP`](QP.md)

Defined in: [WAProto/index.d.ts:26667](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26667)

Decodes a QP message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`QP`](QP.md)

QP

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`QP`](QP.md)

Defined in: [WAProto/index.d.ts:26676](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26676)

Decodes a QP message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`QP`](QP.md)

QP

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26649](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26649)

Encodes the specified QP message. Does not implicitly [verify](QP.md#verify) messages.

#### Parameters

##### message

[`IQP`](../interfaces/IQP.md)

QP message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26657](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26657)

Encodes the specified QP message, length delimited. Does not implicitly [verify](QP.md#verify) messages.

#### Parameters

##### message

[`IQP`](../interfaces/IQP.md)

QP message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`QP`](QP.md)

Defined in: [WAProto/index.d.ts:26690](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26690)

Creates a QP message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`QP`](QP.md)

QP

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:26698](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26698)

Creates a plain object from a QP message. Also converts values to other types if specified.

#### Parameters

##### message

[`QP`](QP.md)

QP

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26683](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26683)

Verifies a QP message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
