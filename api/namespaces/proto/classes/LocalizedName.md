# Class: LocalizedName

Defined in: [WAProto/index.d.ts:8713](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8713)

Represents a LocalizedName.

## Implements

- [`ILocalizedName`](../interfaces/ILocalizedName.md)

## Constructors

### new LocalizedName()

> **new LocalizedName**(`properties`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:8719](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8719)

Constructs a new LocalizedName.

#### Parameters

##### properties?

[`ILocalizedName`](../interfaces/ILocalizedName.md)

Properties to set

#### Returns

[`LocalizedName`](LocalizedName.md)

## Properties

### lc

> **lc**: `string`

Defined in: [WAProto/index.d.ts:8725](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8725)

LocalizedName lc.

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`lc`](../interfaces/ILocalizedName.md#lc)

***

### lg

> **lg**: `string`

Defined in: [WAProto/index.d.ts:8722](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8722)

LocalizedName lg.

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`lg`](../interfaces/ILocalizedName.md#lg)

***

### verifiedName

> **verifiedName**: `string`

Defined in: [WAProto/index.d.ts:8728](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8728)

LocalizedName verifiedName.

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`verifiedName`](../interfaces/ILocalizedName.md#verifiedname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8798](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8798)

Converts this LocalizedName to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:8735](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8735)

Creates a new LocalizedName instance using the specified properties.

#### Parameters

##### properties?

[`ILocalizedName`](../interfaces/ILocalizedName.md)

Properties to set

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:8761](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8761)

Decodes a LocalizedName message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:8770](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8770)

Decodes a LocalizedName message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8743](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8743)

Encodes the specified LocalizedName message. Does not implicitly [verify](LocalizedName.md#verify) messages.

#### Parameters

##### message

[`ILocalizedName`](../interfaces/ILocalizedName.md)

LocalizedName message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8751](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8751)

Encodes the specified LocalizedName message, length delimited. Does not implicitly [verify](LocalizedName.md#verify) messages.

#### Parameters

##### message

[`ILocalizedName`](../interfaces/ILocalizedName.md)

LocalizedName message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:8784](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8784)

Creates a LocalizedName message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8792](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8792)

Creates a plain object from a LocalizedName message. Also converts values to other types if specified.

#### Parameters

##### message

[`LocalizedName`](LocalizedName.md)

LocalizedName

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8777](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8777)

Verifies a LocalizedName message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
