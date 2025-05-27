# Class: Row

Defined in: [WAProto/index.d.ts:17595](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17595)

Represents a Row.

## Implements

- [`IRow`](../interfaces/IRow.md)

## Constructors

### new Row()

> **new Row**(`properties`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:17601](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17601)

Constructs a new Row.

#### Parameters

##### properties?

[`IRow`](../interfaces/IRow.md)

Properties to set

#### Returns

[`Row`](Row.md)

## Properties

### description

> **description**: `string`

Defined in: [WAProto/index.d.ts:17607](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17607)

Row description.

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`description`](../interfaces/IRow.md#description)

***

### rowId

> **rowId**: `string`

Defined in: [WAProto/index.d.ts:17610](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17610)

Row rowId.

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`rowId`](../interfaces/IRow.md#rowid)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:17604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17604)

Row title.

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`title`](../interfaces/IRow.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17680](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17680)

Converts this Row to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:17617](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17617)

Creates a new Row instance using the specified properties.

#### Parameters

##### properties?

[`IRow`](../interfaces/IRow.md)

Properties to set

#### Returns

[`Row`](Row.md)

Row instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:17643](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17643)

Decodes a Row message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Row`](Row.md)

Row

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:17652](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17652)

Decodes a Row message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Row`](Row.md)

Row

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17625)

Encodes the specified Row message. Does not implicitly [verify](Row.md#verify) messages.

#### Parameters

##### message

[`IRow`](../interfaces/IRow.md)

Row message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17633](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17633)

Encodes the specified Row message, length delimited. Does not implicitly [verify](Row.md#verify) messages.

#### Parameters

##### message

[`IRow`](../interfaces/IRow.md)

Row message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:17666](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17666)

Creates a Row message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Row`](Row.md)

Row

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:17674](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17674)

Creates a plain object from a Row message. Also converts values to other types if specified.

#### Parameters

##### message

[`Row`](Row.md)

Row

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17659](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L17659)

Verifies a Row message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
