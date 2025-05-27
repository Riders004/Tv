# Class: ChatAssignmentOpenedStatusAction

Defined in: [WAProto/index.d.ts:30415](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30415)

Represents a ChatAssignmentOpenedStatusAction.

## Implements

- [`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

## Constructors

### new ChatAssignmentOpenedStatusAction()

> **new ChatAssignmentOpenedStatusAction**(`properties`?): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:30421](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30421)

Constructs a new ChatAssignmentOpenedStatusAction.

#### Parameters

##### properties?

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

Properties to set

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

## Properties

### chatOpened

> **chatOpened**: `boolean`

Defined in: [WAProto/index.d.ts:30424](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30424)

ChatAssignmentOpenedStatusAction chatOpened.

#### Implementation of

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md).[`chatOpened`](../interfaces/IChatAssignmentOpenedStatusAction.md#chatopened)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30494](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30494)

Converts this ChatAssignmentOpenedStatusAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:30431](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30431)

Creates a new ChatAssignmentOpenedStatusAction instance using the specified properties.

#### Parameters

##### properties?

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

Properties to set

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

ChatAssignmentOpenedStatusAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:30457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30457)

Decodes a ChatAssignmentOpenedStatusAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

ChatAssignmentOpenedStatusAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:30466](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30466)

Decodes a ChatAssignmentOpenedStatusAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

ChatAssignmentOpenedStatusAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30439](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30439)

Encodes the specified ChatAssignmentOpenedStatusAction message. Does not implicitly [verify](ChatAssignmentOpenedStatusAction.md#verify) messages.

#### Parameters

##### message

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

ChatAssignmentOpenedStatusAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30447](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30447)

Encodes the specified ChatAssignmentOpenedStatusAction message, length delimited. Does not implicitly [verify](ChatAssignmentOpenedStatusAction.md#verify) messages.

#### Parameters

##### message

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

ChatAssignmentOpenedStatusAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:30480](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30480)

Creates a ChatAssignmentOpenedStatusAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

ChatAssignmentOpenedStatusAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30488](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30488)

Creates a plain object from a ChatAssignmentOpenedStatusAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

ChatAssignmentOpenedStatusAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30473](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30473)

Verifies a ChatAssignmentOpenedStatusAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
