# Class: CatalogSnapshot

Defined in: [WAProto/index.d.ts:20843](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20843)

Represents a CatalogSnapshot.

## Implements

- [`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

## Constructors

### new CatalogSnapshot()

> **new CatalogSnapshot**(`properties`?): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:20849](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20849)

Constructs a new CatalogSnapshot.

#### Parameters

##### properties?

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

Properties to set

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

## Properties

### catalogImage?

> `optional` **catalogImage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:20852](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20852)

CatalogSnapshot catalogImage.

#### Implementation of

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md).[`catalogImage`](../interfaces/ICatalogSnapshot.md#catalogimage)

***

### description

> **description**: `string`

Defined in: [WAProto/index.d.ts:20858](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20858)

CatalogSnapshot description.

#### Implementation of

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md).[`description`](../interfaces/ICatalogSnapshot.md#description)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:20855](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20855)

CatalogSnapshot title.

#### Implementation of

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md).[`title`](../interfaces/ICatalogSnapshot.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20928](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20928)

Converts this CatalogSnapshot to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:20865](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20865)

Creates a new CatalogSnapshot instance using the specified properties.

#### Parameters

##### properties?

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

Properties to set

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

CatalogSnapshot instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:20891](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20891)

Decodes a CatalogSnapshot message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

CatalogSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:20900](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20900)

Decodes a CatalogSnapshot message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

CatalogSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20873](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20873)

Encodes the specified CatalogSnapshot message. Does not implicitly [verify](CatalogSnapshot.md#verify) messages.

#### Parameters

##### message

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

CatalogSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20881](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20881)

Encodes the specified CatalogSnapshot message, length delimited. Does not implicitly [verify](CatalogSnapshot.md#verify) messages.

#### Parameters

##### message

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

CatalogSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:20914](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20914)

Creates a CatalogSnapshot message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

CatalogSnapshot

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20922](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20922)

Creates a plain object from a CatalogSnapshot message. Also converts values to other types if specified.

#### Parameters

##### message

[`CatalogSnapshot`](CatalogSnapshot.md)

CatalogSnapshot

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20907](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20907)

Verifies a CatalogSnapshot message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
