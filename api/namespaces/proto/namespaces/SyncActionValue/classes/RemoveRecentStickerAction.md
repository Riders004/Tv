# Class: RemoveRecentStickerAction

Defined in: [WAProto/index.d.ts:33189](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33189)

Represents a RemoveRecentStickerAction.

## Implements

- [`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

## Constructors

### new RemoveRecentStickerAction()

> **new RemoveRecentStickerAction**(`properties`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:33195](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33195)

Constructs a new RemoveRecentStickerAction.

#### Parameters

##### properties?

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

Properties to set

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

## Properties

### lastStickerSentTs

> **lastStickerSentTs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:33198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33198)

RemoveRecentStickerAction lastStickerSentTs.

#### Implementation of

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md).[`lastStickerSentTs`](../interfaces/IRemoveRecentStickerAction.md#laststickersentts)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33268](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33268)

Converts this RemoveRecentStickerAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:33205](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33205)

Creates a new RemoveRecentStickerAction instance using the specified properties.

#### Parameters

##### properties?

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

Properties to set

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:33231](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33231)

Decodes a RemoveRecentStickerAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:33240](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33240)

Decodes a RemoveRecentStickerAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33213](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33213)

Encodes the specified RemoveRecentStickerAction message. Does not implicitly [verify](RemoveRecentStickerAction.md#verify) messages.

#### Parameters

##### message

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

RemoveRecentStickerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33221)

Encodes the specified RemoveRecentStickerAction message, length delimited. Does not implicitly [verify](RemoveRecentStickerAction.md#verify) messages.

#### Parameters

##### message

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

RemoveRecentStickerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:33254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33254)

Creates a RemoveRecentStickerAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33262)

Creates a plain object from a RemoveRecentStickerAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33247](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33247)

Verifies a RemoveRecentStickerAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
