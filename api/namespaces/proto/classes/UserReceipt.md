# Class: UserReceipt

Defined in: [WAProto/index.d.ts:35510](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35510)

Represents a UserReceipt.

## Implements

- [`IUserReceipt`](../interfaces/IUserReceipt.md)

## Constructors

### new UserReceipt()

> **new UserReceipt**(`properties`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:35516](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35516)

Constructs a new UserReceipt.

#### Parameters

##### properties?

[`IUserReceipt`](../interfaces/IUserReceipt.md)

Properties to set

#### Returns

[`UserReceipt`](UserReceipt.md)

## Properties

### deliveredDeviceJid

> **deliveredDeviceJid**: `string`[]

Defined in: [WAProto/index.d.ts:35534](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35534)

UserReceipt deliveredDeviceJid.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`deliveredDeviceJid`](../interfaces/IUserReceipt.md#delivereddevicejid)

***

### pendingDeviceJid

> **pendingDeviceJid**: `string`[]

Defined in: [WAProto/index.d.ts:35531](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35531)

UserReceipt pendingDeviceJid.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`pendingDeviceJid`](../interfaces/IUserReceipt.md#pendingdevicejid)

***

### playedTimestamp

> **playedTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:35528](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35528)

UserReceipt playedTimestamp.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`playedTimestamp`](../interfaces/IUserReceipt.md#playedtimestamp)

***

### readTimestamp

> **readTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:35525](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35525)

UserReceipt readTimestamp.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`readTimestamp`](../interfaces/IUserReceipt.md#readtimestamp)

***

### receiptTimestamp

> **receiptTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:35522](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35522)

UserReceipt receiptTimestamp.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`receiptTimestamp`](../interfaces/IUserReceipt.md#receipttimestamp)

***

### userJid

> **userJid**: `string`

Defined in: [WAProto/index.d.ts:35519](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35519)

UserReceipt userJid.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`userJid`](../interfaces/IUserReceipt.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35604)

Converts this UserReceipt to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:35541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35541)

Creates a new UserReceipt instance using the specified properties.

#### Parameters

##### properties?

[`IUserReceipt`](../interfaces/IUserReceipt.md)

Properties to set

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:35567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35567)

Decodes a UserReceipt message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:35576](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35576)

Decodes a UserReceipt message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35549](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35549)

Encodes the specified UserReceipt message. Does not implicitly [verify](UserReceipt.md#verify) messages.

#### Parameters

##### message

[`IUserReceipt`](../interfaces/IUserReceipt.md)

UserReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35557](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35557)

Encodes the specified UserReceipt message, length delimited. Does not implicitly [verify](UserReceipt.md#verify) messages.

#### Parameters

##### message

[`IUserReceipt`](../interfaces/IUserReceipt.md)

UserReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:35590](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35590)

Creates a UserReceipt message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35598](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35598)

Creates a plain object from a UserReceipt message. Also converts values to other types if specified.

#### Parameters

##### message

[`UserReceipt`](UserReceipt.md)

UserReceipt

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35583](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35583)

Verifies a UserReceipt message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
