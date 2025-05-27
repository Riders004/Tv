# Class: SyncActionData

Defined in: [WAProto/index.d.ts:29414](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29414)

Represents a SyncActionData.

## Implements

- [`ISyncActionData`](../interfaces/ISyncActionData.md)

## Constructors

### new SyncActionData()

> **new SyncActionData**(`properties`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:29420](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29420)

Constructs a new SyncActionData.

#### Parameters

##### properties?

[`ISyncActionData`](../interfaces/ISyncActionData.md)

Properties to set

#### Returns

[`SyncActionData`](SyncActionData.md)

## Properties

### index

> **index**: `Uint8Array`

Defined in: [WAProto/index.d.ts:29423](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29423)

SyncActionData index.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`index`](../interfaces/ISyncActionData.md#index)

***

### padding

> **padding**: `Uint8Array`

Defined in: [WAProto/index.d.ts:29429](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29429)

SyncActionData padding.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`padding`](../interfaces/ISyncActionData.md#padding)

***

### value?

> `optional` **value**: `null` \| [`ISyncActionValue`](../interfaces/ISyncActionValue.md)

Defined in: [WAProto/index.d.ts:29426](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29426)

SyncActionData value.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`value`](../interfaces/ISyncActionData.md#value)

***

### version

> **version**: `number`

Defined in: [WAProto/index.d.ts:29432](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29432)

SyncActionData version.

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`version`](../interfaces/ISyncActionData.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29502](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29502)

Converts this SyncActionData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:29439](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29439)

Creates a new SyncActionData instance using the specified properties.

#### Parameters

##### properties?

[`ISyncActionData`](../interfaces/ISyncActionData.md)

Properties to set

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:29465](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29465)

Decodes a SyncActionData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:29474](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29474)

Decodes a SyncActionData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29447](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29447)

Encodes the specified SyncActionData message. Does not implicitly [verify](SyncActionData.md#verify) messages.

#### Parameters

##### message

[`ISyncActionData`](../interfaces/ISyncActionData.md)

SyncActionData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29455)

Encodes the specified SyncActionData message, length delimited. Does not implicitly [verify](SyncActionData.md#verify) messages.

#### Parameters

##### message

[`ISyncActionData`](../interfaces/ISyncActionData.md)

SyncActionData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:29488](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29488)

Creates a SyncActionData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncActionData`](SyncActionData.md)

SyncActionData

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:29496](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29496)

Creates a plain object from a SyncActionData message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncActionData`](SyncActionData.md)

SyncActionData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29481](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29481)

Verifies a SyncActionData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
