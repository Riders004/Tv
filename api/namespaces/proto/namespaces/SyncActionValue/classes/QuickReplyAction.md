# Class: QuickReplyAction

Defined in: [WAProto/index.d.ts:32997](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32997)

Represents a QuickReplyAction.

## Implements

- [`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

## Constructors

### new QuickReplyAction()

> **new QuickReplyAction**(`properties`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:33003](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33003)

Constructs a new QuickReplyAction.

#### Parameters

##### properties?

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

Properties to set

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

## Properties

### count

> **count**: `number`

Defined in: [WAProto/index.d.ts:33015](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33015)

QuickReplyAction count.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`count`](../interfaces/IQuickReplyAction.md#count)

***

### deleted

> **deleted**: `boolean`

Defined in: [WAProto/index.d.ts:33018](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33018)

QuickReplyAction deleted.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`deleted`](../interfaces/IQuickReplyAction.md#deleted)

***

### keywords

> **keywords**: `string`[]

Defined in: [WAProto/index.d.ts:33012](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33012)

QuickReplyAction keywords.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`keywords`](../interfaces/IQuickReplyAction.md#keywords)

***

### message

> **message**: `string`

Defined in: [WAProto/index.d.ts:33009](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33009)

QuickReplyAction message.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`message`](../interfaces/IQuickReplyAction.md#message)

***

### shortcut

> **shortcut**: `string`

Defined in: [WAProto/index.d.ts:33006](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33006)

QuickReplyAction shortcut.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`shortcut`](../interfaces/IQuickReplyAction.md#shortcut)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33088](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33088)

Converts this QuickReplyAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:33025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33025)

Creates a new QuickReplyAction instance using the specified properties.

#### Parameters

##### properties?

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

Properties to set

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:33051](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33051)

Decodes a QuickReplyAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:33060](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33060)

Decodes a QuickReplyAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33033](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33033)

Encodes the specified QuickReplyAction message. Does not implicitly [verify](QuickReplyAction.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

QuickReplyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33041](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33041)

Encodes the specified QuickReplyAction message, length delimited. Does not implicitly [verify](QuickReplyAction.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

QuickReplyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:33074](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33074)

Creates a QuickReplyAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33082](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33082)

Creates a plain object from a QuickReplyAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33067](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33067)

Verifies a QuickReplyAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
