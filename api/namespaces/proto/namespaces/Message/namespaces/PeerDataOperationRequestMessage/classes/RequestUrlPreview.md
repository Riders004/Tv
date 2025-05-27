# Class: RequestUrlPreview

Defined in: [WAProto/index.d.ts:19250](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19250)

Represents a RequestUrlPreview.

## Implements

- [`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

## Constructors

### new RequestUrlPreview()

> **new RequestUrlPreview**(`properties`?): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:19256](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19256)

Constructs a new RequestUrlPreview.

#### Parameters

##### properties?

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

Properties to set

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

## Properties

### includeHqThumbnail

> **includeHqThumbnail**: `boolean`

Defined in: [WAProto/index.d.ts:19262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19262)

RequestUrlPreview includeHqThumbnail.

#### Implementation of

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md).[`includeHqThumbnail`](../interfaces/IRequestUrlPreview.md#includehqthumbnail)

***

### url

> **url**: `string`

Defined in: [WAProto/index.d.ts:19259](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19259)

RequestUrlPreview url.

#### Implementation of

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md).[`url`](../interfaces/IRequestUrlPreview.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19332](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19332)

Converts this RequestUrlPreview to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:19269](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19269)

Creates a new RequestUrlPreview instance using the specified properties.

#### Parameters

##### properties?

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

Properties to set

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

RequestUrlPreview instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:19295](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19295)

Decodes a RequestUrlPreview message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

RequestUrlPreview

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:19304](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19304)

Decodes a RequestUrlPreview message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

RequestUrlPreview

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19277)

Encodes the specified RequestUrlPreview message. Does not implicitly [verify](RequestUrlPreview.md#verify) messages.

#### Parameters

##### message

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

RequestUrlPreview message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19285](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19285)

Encodes the specified RequestUrlPreview message, length delimited. Does not implicitly [verify](RequestUrlPreview.md#verify) messages.

#### Parameters

##### message

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

RequestUrlPreview message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:19318](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19318)

Creates a RequestUrlPreview message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

RequestUrlPreview

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:19326](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19326)

Creates a plain object from a RequestUrlPreview message. Also converts values to other types if specified.

#### Parameters

##### message

[`RequestUrlPreview`](RequestUrlPreview.md)

RequestUrlPreview

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19311](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19311)

Verifies a RequestUrlPreview message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
