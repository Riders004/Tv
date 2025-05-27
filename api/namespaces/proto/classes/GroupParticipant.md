# Class: GroupParticipant

Defined in: [WAProto/index.d.ts:6953](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6953)

Represents a GroupParticipant.

## Implements

- [`IGroupParticipant`](../interfaces/IGroupParticipant.md)

## Constructors

### new GroupParticipant()

> **new GroupParticipant**(`properties`?): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:6959](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6959)

Constructs a new GroupParticipant.

#### Parameters

##### properties?

[`IGroupParticipant`](../interfaces/IGroupParticipant.md)

Properties to set

#### Returns

[`GroupParticipant`](GroupParticipant.md)

## Properties

### rank

> **rank**: [`Rank`](../namespaces/GroupParticipant/enumerations/Rank.md)

Defined in: [WAProto/index.d.ts:6965](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6965)

GroupParticipant rank.

#### Implementation of

[`IGroupParticipant`](../interfaces/IGroupParticipant.md).[`rank`](../interfaces/IGroupParticipant.md#rank)

***

### userJid

> **userJid**: `string`

Defined in: [WAProto/index.d.ts:6962](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6962)

GroupParticipant userJid.

#### Implementation of

[`IGroupParticipant`](../interfaces/IGroupParticipant.md).[`userJid`](../interfaces/IGroupParticipant.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7035](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7035)

Converts this GroupParticipant to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:6972](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6972)

Creates a new GroupParticipant instance using the specified properties.

#### Parameters

##### properties?

[`IGroupParticipant`](../interfaces/IGroupParticipant.md)

Properties to set

#### Returns

[`GroupParticipant`](GroupParticipant.md)

GroupParticipant instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:6998](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6998)

Decodes a GroupParticipant message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`GroupParticipant`](GroupParticipant.md)

GroupParticipant

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:7007](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7007)

Decodes a GroupParticipant message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`GroupParticipant`](GroupParticipant.md)

GroupParticipant

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6980](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6980)

Encodes the specified GroupParticipant message. Does not implicitly [verify](GroupParticipant.md#verify) messages.

#### Parameters

##### message

[`IGroupParticipant`](../interfaces/IGroupParticipant.md)

GroupParticipant message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6988](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6988)

Encodes the specified GroupParticipant message, length delimited. Does not implicitly [verify](GroupParticipant.md#verify) messages.

#### Parameters

##### message

[`IGroupParticipant`](../interfaces/IGroupParticipant.md)

GroupParticipant message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:7021](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7021)

Creates a GroupParticipant message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`GroupParticipant`](GroupParticipant.md)

GroupParticipant

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:7029](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7029)

Creates a plain object from a GroupParticipant message. Also converts values to other types if specified.

#### Parameters

##### message

[`GroupParticipant`](GroupParticipant.md)

GroupParticipant

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7014](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7014)

Verifies a GroupParticipant message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
