# Class: MessageHistoryBundle

Defined in: [WAProto/index.d.ts:18322](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18322)

Represents a MessageHistoryBundle.

## Implements

- [`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

## Constructors

### new MessageHistoryBundle()

> **new MessageHistoryBundle**(`properties`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:18328](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18328)

Constructs a new MessageHistoryBundle.

#### Parameters

##### properties?

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

Properties to set

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:18349](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18349)

MessageHistoryBundle contextInfo.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`contextInfo`](../interfaces/IMessageHistoryBundle.md#contextinfo)

***

### directPath

> **directPath**: `string`

Defined in: [WAProto/index.d.ts:18343](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18343)

MessageHistoryBundle directPath.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`directPath`](../interfaces/IMessageHistoryBundle.md#directpath)

***

### fileEncSha256

> **fileEncSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:18340](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18340)

MessageHistoryBundle fileEncSha256.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`fileEncSha256`](../interfaces/IMessageHistoryBundle.md#fileencsha256)

***

### fileSha256

> **fileSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:18334](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18334)

MessageHistoryBundle fileSha256.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`fileSha256`](../interfaces/IMessageHistoryBundle.md#filesha256)

***

### mediaKey

> **mediaKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:18337](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18337)

MessageHistoryBundle mediaKey.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mediaKey`](../interfaces/IMessageHistoryBundle.md#mediakey)

***

### mediaKeyTimestamp

> **mediaKeyTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:18346](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18346)

MessageHistoryBundle mediaKeyTimestamp.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mediaKeyTimestamp`](../interfaces/IMessageHistoryBundle.md#mediakeytimestamp)

***

### mimetype

> **mimetype**: `string`

Defined in: [WAProto/index.d.ts:18331](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18331)

MessageHistoryBundle mimetype.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mimetype`](../interfaces/IMessageHistoryBundle.md#mimetype)

***

### participants

> **participants**: `string`[]

Defined in: [WAProto/index.d.ts:18352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18352)

MessageHistoryBundle participants.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`participants`](../interfaces/IMessageHistoryBundle.md#participants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:18422](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18422)

Converts this MessageHistoryBundle to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:18359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18359)

Creates a new MessageHistoryBundle instance using the specified properties.

#### Parameters

##### properties?

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

Properties to set

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:18385](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18385)

Decodes a MessageHistoryBundle message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:18394](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18394)

Decodes a MessageHistoryBundle message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18367](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18367)

Encodes the specified MessageHistoryBundle message. Does not implicitly [verify](MessageHistoryBundle.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

MessageHistoryBundle message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18375](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18375)

Encodes the specified MessageHistoryBundle message, length delimited. Does not implicitly [verify](MessageHistoryBundle.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

MessageHistoryBundle message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:18408](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18408)

Creates a MessageHistoryBundle message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:18416](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18416)

Creates a plain object from a MessageHistoryBundle message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:18401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18401)

Verifies a MessageHistoryBundle message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
