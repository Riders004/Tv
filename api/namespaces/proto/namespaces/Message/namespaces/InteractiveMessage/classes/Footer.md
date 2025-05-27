# Class: Footer

Defined in: [WAProto/index.d.ts:15954](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15954)

Represents a Footer.

## Implements

- [`IFooter`](../interfaces/IFooter.md)

## Constructors

### new Footer()

> **new Footer**(`properties`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:15960](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15960)

Constructs a new Footer.

#### Parameters

##### properties?

[`IFooter`](../interfaces/IFooter.md)

Properties to set

#### Returns

[`Footer`](Footer.md)

## Properties

### text

> **text**: `string`

Defined in: [WAProto/index.d.ts:15963](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15963)

Footer text.

#### Implementation of

[`IFooter`](../interfaces/IFooter.md).[`text`](../interfaces/IFooter.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16033](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16033)

Converts this Footer to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:15970](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15970)

Creates a new Footer instance using the specified properties.

#### Parameters

##### properties?

[`IFooter`](../interfaces/IFooter.md)

Properties to set

#### Returns

[`Footer`](Footer.md)

Footer instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:15996](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15996)

Decodes a Footer message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Footer`](Footer.md)

Footer

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:16005](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16005)

Decodes a Footer message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Footer`](Footer.md)

Footer

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15978](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15978)

Encodes the specified Footer message. Does not implicitly [verify](Footer.md#verify) messages.

#### Parameters

##### message

[`IFooter`](../interfaces/IFooter.md)

Footer message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15986](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15986)

Encodes the specified Footer message, length delimited. Does not implicitly [verify](Footer.md#verify) messages.

#### Parameters

##### message

[`IFooter`](../interfaces/IFooter.md)

Footer message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:16019](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16019)

Creates a Footer message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Footer`](Footer.md)

Footer

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16027](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16027)

Creates a plain object from a Footer message. Also converts values to other types if specified.

#### Parameters

##### message

[`Footer`](Footer.md)

Footer

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16012](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16012)

Verifies a Footer message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
