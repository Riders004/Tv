# Class: DeleteChatAction

Defined in: [WAProto/index.d.ts:30997](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30997)

Represents a DeleteChatAction.

## Implements

- [`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

## Constructors

### new DeleteChatAction()

> **new DeleteChatAction**(`properties`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:31003](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31003)

Constructs a new DeleteChatAction.

#### Parameters

##### properties?

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

Properties to set

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

## Properties

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:31006](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31006)

DeleteChatAction messageRange.

#### Implementation of

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md).[`messageRange`](../interfaces/IDeleteChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31076](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31076)

Converts this DeleteChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:31013](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31013)

Creates a new DeleteChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

Properties to set

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:31039](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31039)

Decodes a DeleteChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:31048](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31048)

Decodes a DeleteChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31021](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31021)

Encodes the specified DeleteChatAction message. Does not implicitly [verify](DeleteChatAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

DeleteChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31029](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31029)

Encodes the specified DeleteChatAction message, length delimited. Does not implicitly [verify](DeleteChatAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

DeleteChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:31062](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31062)

Creates a DeleteChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31070](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31070)

Creates a plain object from a DeleteChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31055](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31055)

Verifies a DeleteChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
