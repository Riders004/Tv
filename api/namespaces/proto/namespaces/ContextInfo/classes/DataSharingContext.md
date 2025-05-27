# Class: DataSharingContext

Defined in: [WAProto/index.d.ts:4643](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4643)

Represents a DataSharingContext.

## Implements

- [`IDataSharingContext`](../interfaces/IDataSharingContext.md)

## Constructors

### new DataSharingContext()

> **new DataSharingContext**(`properties`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:4649](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4649)

Constructs a new DataSharingContext.

#### Parameters

##### properties?

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

Properties to set

#### Returns

[`DataSharingContext`](DataSharingContext.md)

## Properties

### showMmDisclosure

> **showMmDisclosure**: `boolean`

Defined in: [WAProto/index.d.ts:4652](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4652)

DataSharingContext showMmDisclosure.

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`showMmDisclosure`](../interfaces/IDataSharingContext.md#showmmdisclosure)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4722](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4722)

Converts this DataSharingContext to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:4659](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4659)

Creates a new DataSharingContext instance using the specified properties.

#### Parameters

##### properties?

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

Properties to set

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:4685](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4685)

Decodes a DataSharingContext message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:4694](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4694)

Decodes a DataSharingContext message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4667](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4667)

Encodes the specified DataSharingContext message. Does not implicitly [verify](DataSharingContext.md#verify) messages.

#### Parameters

##### message

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

DataSharingContext message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4675](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4675)

Encodes the specified DataSharingContext message, length delimited. Does not implicitly [verify](DataSharingContext.md#verify) messages.

#### Parameters

##### message

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

DataSharingContext message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:4708](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4708)

Creates a DataSharingContext message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:4716](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4716)

Creates a plain object from a DataSharingContext message. Also converts values to other types if specified.

#### Parameters

##### message

[`DataSharingContext`](DataSharingContext.md)

DataSharingContext

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4701](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4701)

Verifies a DataSharingContext message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
