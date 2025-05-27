# Class: PhotoChange

Defined in: [WAProto/index.d.ts:25595](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25595)

Represents a PhotoChange.

## Implements

- [`IPhotoChange`](../interfaces/IPhotoChange.md)

## Constructors

### new PhotoChange()

> **new PhotoChange**(`properties`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:25601](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25601)

Constructs a new PhotoChange.

#### Parameters

##### properties?

[`IPhotoChange`](../interfaces/IPhotoChange.md)

Properties to set

#### Returns

[`PhotoChange`](PhotoChange.md)

## Properties

### newPhoto

> **newPhoto**: `Uint8Array`

Defined in: [WAProto/index.d.ts:25607](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25607)

PhotoChange newPhoto.

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`newPhoto`](../interfaces/IPhotoChange.md#newphoto)

***

### newPhotoId

> **newPhotoId**: `number`

Defined in: [WAProto/index.d.ts:25610](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25610)

PhotoChange newPhotoId.

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`newPhotoId`](../interfaces/IPhotoChange.md#newphotoid)

***

### oldPhoto

> **oldPhoto**: `Uint8Array`

Defined in: [WAProto/index.d.ts:25604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25604)

PhotoChange oldPhoto.

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`oldPhoto`](../interfaces/IPhotoChange.md#oldphoto)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25680](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25680)

Converts this PhotoChange to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:25617](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25617)

Creates a new PhotoChange instance using the specified properties.

#### Parameters

##### properties?

[`IPhotoChange`](../interfaces/IPhotoChange.md)

Properties to set

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:25643](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25643)

Decodes a PhotoChange message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:25652](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25652)

Decodes a PhotoChange message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25625)

Encodes the specified PhotoChange message. Does not implicitly [verify](PhotoChange.md#verify) messages.

#### Parameters

##### message

[`IPhotoChange`](../interfaces/IPhotoChange.md)

PhotoChange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25633](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25633)

Encodes the specified PhotoChange message, length delimited. Does not implicitly [verify](PhotoChange.md#verify) messages.

#### Parameters

##### message

[`IPhotoChange`](../interfaces/IPhotoChange.md)

PhotoChange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:25666](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25666)

Creates a PhotoChange message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:25674](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25674)

Creates a plain object from a PhotoChange message. Also converts values to other types if specified.

#### Parameters

##### message

[`PhotoChange`](PhotoChange.md)

PhotoChange

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25659](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25659)

Verifies a PhotoChange message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
