# Class: ArchiveChatAction

Defined in: [WAProto/index.d.ts:30052](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30052)

Represents an ArchiveChatAction.

## Implements

- [`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

## Constructors

### new ArchiveChatAction()

> **new ArchiveChatAction**(`properties`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:30058](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30058)

Constructs a new ArchiveChatAction.

#### Parameters

##### properties?

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

Properties to set

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

## Properties

### archived

> **archived**: `boolean`

Defined in: [WAProto/index.d.ts:30061](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30061)

ArchiveChatAction archived.

#### Implementation of

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md).[`archived`](../interfaces/IArchiveChatAction.md#archived)

***

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:30064](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30064)

ArchiveChatAction messageRange.

#### Implementation of

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md).[`messageRange`](../interfaces/IArchiveChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30134](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30134)

Converts this ArchiveChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:30071](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30071)

Creates a new ArchiveChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

Properties to set

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:30097](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30097)

Decodes an ArchiveChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:30106](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30106)

Decodes an ArchiveChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30079](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30079)

Encodes the specified ArchiveChatAction message. Does not implicitly [verify](ArchiveChatAction.md#verify) messages.

#### Parameters

##### message

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

ArchiveChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30087](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30087)

Encodes the specified ArchiveChatAction message, length delimited. Does not implicitly [verify](ArchiveChatAction.md#verify) messages.

#### Parameters

##### message

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

ArchiveChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:30120](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30120)

Creates an ArchiveChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30128](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30128)

Creates a plain object from an ArchiveChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30113](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30113)

Verifies an ArchiveChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
