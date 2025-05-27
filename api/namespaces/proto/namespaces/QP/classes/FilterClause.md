# Class: FilterClause

Defined in: [WAProto/index.d.ts:26838](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26838)

Represents a FilterClause.

## Implements

- [`IFilterClause`](../interfaces/IFilterClause.md)

## Constructors

### new FilterClause()

> **new FilterClause**(`properties`?): [`FilterClause`](FilterClause.md)

Defined in: [WAProto/index.d.ts:26844](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26844)

Constructs a new FilterClause.

#### Parameters

##### properties?

[`IFilterClause`](../interfaces/IFilterClause.md)

Properties to set

#### Returns

[`FilterClause`](FilterClause.md)

## Properties

### clauses

> **clauses**: [`IFilterClause`](../interfaces/IFilterClause.md)[]

Defined in: [WAProto/index.d.ts:26850](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26850)

FilterClause clauses.

#### Implementation of

[`IFilterClause`](../interfaces/IFilterClause.md).[`clauses`](../interfaces/IFilterClause.md#clauses)

***

### clauseType

> **clauseType**: [`ClauseType`](../enumerations/ClauseType.md)

Defined in: [WAProto/index.d.ts:26847](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26847)

FilterClause clauseType.

#### Implementation of

[`IFilterClause`](../interfaces/IFilterClause.md).[`clauseType`](../interfaces/IFilterClause.md#clausetype)

***

### filters

> **filters**: [`IFilter`](../interfaces/IFilter.md)[]

Defined in: [WAProto/index.d.ts:26853](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26853)

FilterClause filters.

#### Implementation of

[`IFilterClause`](../interfaces/IFilterClause.md).[`filters`](../interfaces/IFilterClause.md#filters)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26923](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26923)

Converts this FilterClause to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`FilterClause`](FilterClause.md)

Defined in: [WAProto/index.d.ts:26860](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26860)

Creates a new FilterClause instance using the specified properties.

#### Parameters

##### properties?

[`IFilterClause`](../interfaces/IFilterClause.md)

Properties to set

#### Returns

[`FilterClause`](FilterClause.md)

FilterClause instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`FilterClause`](FilterClause.md)

Defined in: [WAProto/index.d.ts:26886](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26886)

Decodes a FilterClause message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`FilterClause`](FilterClause.md)

FilterClause

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`FilterClause`](FilterClause.md)

Defined in: [WAProto/index.d.ts:26895](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26895)

Decodes a FilterClause message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`FilterClause`](FilterClause.md)

FilterClause

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26868](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26868)

Encodes the specified FilterClause message. Does not implicitly [verify](FilterClause.md#verify) messages.

#### Parameters

##### message

[`IFilterClause`](../interfaces/IFilterClause.md)

FilterClause message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26876](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26876)

Encodes the specified FilterClause message, length delimited. Does not implicitly [verify](FilterClause.md#verify) messages.

#### Parameters

##### message

[`IFilterClause`](../interfaces/IFilterClause.md)

FilterClause message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`FilterClause`](FilterClause.md)

Defined in: [WAProto/index.d.ts:26909](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26909)

Creates a FilterClause message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`FilterClause`](FilterClause.md)

FilterClause

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:26917](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26917)

Creates a plain object from a FilterClause message. Also converts values to other types if specified.

#### Parameters

##### message

[`FilterClause`](FilterClause.md)

FilterClause

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26902](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26902)

Verifies a FilterClause message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
