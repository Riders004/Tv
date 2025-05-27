# Class: GroupMention

Defined in: [WAProto/index.d.ts:6857](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6857)

Represents a GroupMention.

## Implements

- [`IGroupMention`](../interfaces/IGroupMention.md)

## Constructors

### new GroupMention()

> **new GroupMention**(`properties`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:6863](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6863)

Constructs a new GroupMention.

#### Parameters

##### properties?

[`IGroupMention`](../interfaces/IGroupMention.md)

Properties to set

#### Returns

[`GroupMention`](GroupMention.md)

## Properties

### groupJid

> **groupJid**: `string`

Defined in: [WAProto/index.d.ts:6866](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6866)

GroupMention groupJid.

#### Implementation of

[`IGroupMention`](../interfaces/IGroupMention.md).[`groupJid`](../interfaces/IGroupMention.md#groupjid)

***

### groupSubject

> **groupSubject**: `string`

Defined in: [WAProto/index.d.ts:6869](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6869)

GroupMention groupSubject.

#### Implementation of

[`IGroupMention`](../interfaces/IGroupMention.md).[`groupSubject`](../interfaces/IGroupMention.md#groupsubject)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6939](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6939)

Converts this GroupMention to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:6876](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6876)

Creates a new GroupMention instance using the specified properties.

#### Parameters

##### properties?

[`IGroupMention`](../interfaces/IGroupMention.md)

Properties to set

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:6902](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6902)

Decodes a GroupMention message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:6911](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6911)

Decodes a GroupMention message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6884](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6884)

Encodes the specified GroupMention message. Does not implicitly [verify](GroupMention.md#verify) messages.

#### Parameters

##### message

[`IGroupMention`](../interfaces/IGroupMention.md)

GroupMention message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6892](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6892)

Encodes the specified GroupMention message, length delimited. Does not implicitly [verify](GroupMention.md#verify) messages.

#### Parameters

##### message

[`IGroupMention`](../interfaces/IGroupMention.md)

GroupMention message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:6925](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6925)

Creates a GroupMention message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:6933](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6933)

Creates a plain object from a GroupMention message. Also converts values to other types if specified.

#### Parameters

##### message

[`GroupMention`](GroupMention.md)

GroupMention

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6918](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6918)

Verifies a GroupMention message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
