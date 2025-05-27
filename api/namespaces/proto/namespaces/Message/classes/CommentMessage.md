# Class: CommentMessage

Defined in: [WAProto/index.d.ts:12331](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12331)

Represents a CommentMessage.

## Implements

- [`ICommentMessage`](../interfaces/ICommentMessage.md)

## Constructors

### new CommentMessage()

> **new CommentMessage**(`properties`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:12337](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12337)

Constructs a new CommentMessage.

#### Parameters

##### properties?

[`ICommentMessage`](../interfaces/ICommentMessage.md)

Properties to set

#### Returns

[`CommentMessage`](CommentMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:12340](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12340)

CommentMessage message.

#### Implementation of

[`ICommentMessage`](../interfaces/ICommentMessage.md).[`message`](../interfaces/ICommentMessage.md#message)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:12343](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12343)

CommentMessage targetMessageKey.

#### Implementation of

[`ICommentMessage`](../interfaces/ICommentMessage.md).[`targetMessageKey`](../interfaces/ICommentMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12413](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12413)

Converts this CommentMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:12350](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12350)

Creates a new CommentMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICommentMessage`](../interfaces/ICommentMessage.md)

Properties to set

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:12376](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12376)

Decodes a CommentMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:12385](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12385)

Decodes a CommentMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12358](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12358)

Encodes the specified CommentMessage message. Does not implicitly [verify](CommentMessage.md#verify) messages.

#### Parameters

##### message

[`ICommentMessage`](../interfaces/ICommentMessage.md)

CommentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12366](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12366)

Encodes the specified CommentMessage message, length delimited. Does not implicitly [verify](CommentMessage.md#verify) messages.

#### Parameters

##### message

[`ICommentMessage`](../interfaces/ICommentMessage.md)

CommentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:12399](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12399)

Creates a CommentMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12407](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12407)

Creates a plain object from a CommentMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CommentMessage`](CommentMessage.md)

CommentMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12392](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12392)

Verifies a CommentMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
