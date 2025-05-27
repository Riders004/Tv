# Class: Filter

Defined in: [WAProto/index.d.ts:26733](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26733)

Represents a Filter.

## Implements

- [`IFilter`](../interfaces/IFilter.md)

## Constructors

### new Filter()

> **new Filter**(`properties`?): [`Filter`](Filter.md)

Defined in: [WAProto/index.d.ts:26739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26739)

Constructs a new Filter.

#### Parameters

##### properties?

[`IFilter`](../interfaces/IFilter.md)

Properties to set

#### Returns

[`Filter`](Filter.md)

## Properties

### clientNotSupportedConfig

> **clientNotSupportedConfig**: [`FilterClientNotSupportedConfig`](../enumerations/FilterClientNotSupportedConfig.md)

Defined in: [WAProto/index.d.ts:26751](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26751)

Filter clientNotSupportedConfig.

#### Implementation of

[`IFilter`](../interfaces/IFilter.md).[`clientNotSupportedConfig`](../interfaces/IFilter.md#clientnotsupportedconfig)

***

### filterName

> **filterName**: `string`

Defined in: [WAProto/index.d.ts:26742](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26742)

Filter filterName.

#### Implementation of

[`IFilter`](../interfaces/IFilter.md).[`filterName`](../interfaces/IFilter.md#filtername)

***

### filterResult

> **filterResult**: [`FilterResult`](../enumerations/FilterResult.md)

Defined in: [WAProto/index.d.ts:26748](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26748)

Filter filterResult.

#### Implementation of

[`IFilter`](../interfaces/IFilter.md).[`filterResult`](../interfaces/IFilter.md#filterresult)

***

### parameters

> **parameters**: [`IFilterParameters`](../interfaces/IFilterParameters.md)[]

Defined in: [WAProto/index.d.ts:26745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26745)

Filter parameters.

#### Implementation of

[`IFilter`](../interfaces/IFilter.md).[`parameters`](../interfaces/IFilter.md#parameters)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26821](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26821)

Converts this Filter to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Filter`](Filter.md)

Defined in: [WAProto/index.d.ts:26758](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26758)

Creates a new Filter instance using the specified properties.

#### Parameters

##### properties?

[`IFilter`](../interfaces/IFilter.md)

Properties to set

#### Returns

[`Filter`](Filter.md)

Filter instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Filter`](Filter.md)

Defined in: [WAProto/index.d.ts:26784](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26784)

Decodes a Filter message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Filter`](Filter.md)

Filter

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Filter`](Filter.md)

Defined in: [WAProto/index.d.ts:26793](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26793)

Decodes a Filter message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Filter`](Filter.md)

Filter

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26766](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26766)

Encodes the specified Filter message. Does not implicitly [verify](Filter.md#verify) messages.

#### Parameters

##### message

[`IFilter`](../interfaces/IFilter.md)

Filter message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26774](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26774)

Encodes the specified Filter message, length delimited. Does not implicitly [verify](Filter.md#verify) messages.

#### Parameters

##### message

[`IFilter`](../interfaces/IFilter.md)

Filter message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Filter`](Filter.md)

Defined in: [WAProto/index.d.ts:26807](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26807)

Creates a Filter message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Filter`](Filter.md)

Filter

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:26815](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26815)

Creates a plain object from a Filter message. Also converts values to other types if specified.

#### Parameters

##### message

[`Filter`](Filter.md)

Filter

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26800](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26800)

Verifies a Filter message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
