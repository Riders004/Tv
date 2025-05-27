# Class: Body

Defined in: [WAProto/index.d.ts:15666](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15666)

Represents a Body.

## Implements

- [`IBody`](../interfaces/IBody.md)

## Constructors

### new Body()

> **new Body**(`properties`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:15672](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15672)

Constructs a new Body.

#### Parameters

##### properties?

[`IBody`](../interfaces/IBody.md)

Properties to set

#### Returns

[`Body`](Body.md)

## Properties

### text

> **text**: `string`

Defined in: [WAProto/index.d.ts:15675](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15675)

Body text.

#### Implementation of

[`IBody`](../interfaces/IBody.md).[`text`](../interfaces/IBody.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15745)

Converts this Body to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:15682](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15682)

Creates a new Body instance using the specified properties.

#### Parameters

##### properties?

[`IBody`](../interfaces/IBody.md)

Properties to set

#### Returns

[`Body`](Body.md)

Body instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:15708](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15708)

Decodes a Body message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Body`](Body.md)

Body

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:15717](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15717)

Decodes a Body message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Body`](Body.md)

Body

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15690](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15690)

Encodes the specified Body message. Does not implicitly [verify](Body.md#verify) messages.

#### Parameters

##### message

[`IBody`](../interfaces/IBody.md)

Body message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15698](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15698)

Encodes the specified Body message, length delimited. Does not implicitly [verify](Body.md#verify) messages.

#### Parameters

##### message

[`IBody`](../interfaces/IBody.md)

Body message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:15731](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15731)

Creates a Body message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Body`](Body.md)

Body

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:15739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15739)

Creates a plain object from a Body message. Also converts values to other types if specified.

#### Parameters

##### message

[`Body`](Body.md)

Body

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15724)

Verifies a Body message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
