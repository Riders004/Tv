# Class: FilterParameters

Defined in: [WAProto/index.d.ts:26943](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26943)

Represents a FilterParameters.

## Implements

- [`IFilterParameters`](../interfaces/IFilterParameters.md)

## Constructors

### new FilterParameters()

> **new FilterParameters**(`properties`?): [`FilterParameters`](FilterParameters.md)

Defined in: [WAProto/index.d.ts:26949](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26949)

Constructs a new FilterParameters.

#### Parameters

##### properties?

[`IFilterParameters`](../interfaces/IFilterParameters.md)

Properties to set

#### Returns

[`FilterParameters`](FilterParameters.md)

## Properties

### key

> **key**: `string`

Defined in: [WAProto/index.d.ts:26952](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26952)

FilterParameters key.

#### Implementation of

[`IFilterParameters`](../interfaces/IFilterParameters.md).[`key`](../interfaces/IFilterParameters.md#key)

***

### value

> **value**: `string`

Defined in: [WAProto/index.d.ts:26955](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26955)

FilterParameters value.

#### Implementation of

[`IFilterParameters`](../interfaces/IFilterParameters.md).[`value`](../interfaces/IFilterParameters.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27025)

Converts this FilterParameters to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`FilterParameters`](FilterParameters.md)

Defined in: [WAProto/index.d.ts:26962](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26962)

Creates a new FilterParameters instance using the specified properties.

#### Parameters

##### properties?

[`IFilterParameters`](../interfaces/IFilterParameters.md)

Properties to set

#### Returns

[`FilterParameters`](FilterParameters.md)

FilterParameters instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`FilterParameters`](FilterParameters.md)

Defined in: [WAProto/index.d.ts:26988](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26988)

Decodes a FilterParameters message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`FilterParameters`](FilterParameters.md)

FilterParameters

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`FilterParameters`](FilterParameters.md)

Defined in: [WAProto/index.d.ts:26997](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26997)

Decodes a FilterParameters message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`FilterParameters`](FilterParameters.md)

FilterParameters

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26970](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26970)

Encodes the specified FilterParameters message. Does not implicitly [verify](FilterParameters.md#verify) messages.

#### Parameters

##### message

[`IFilterParameters`](../interfaces/IFilterParameters.md)

FilterParameters message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26978](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26978)

Encodes the specified FilterParameters message, length delimited. Does not implicitly [verify](FilterParameters.md#verify) messages.

#### Parameters

##### message

[`IFilterParameters`](../interfaces/IFilterParameters.md)

FilterParameters message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`FilterParameters`](FilterParameters.md)

Defined in: [WAProto/index.d.ts:27011](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27011)

Creates a FilterParameters message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`FilterParameters`](FilterParameters.md)

FilterParameters

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27019](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27019)

Creates a plain object from a FilterParameters message. Also converts values to other types if specified.

#### Parameters

##### message

[`FilterParameters`](FilterParameters.md)

FilterParameters

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27004](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27004)

Verifies a FilterParameters message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
