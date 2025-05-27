# Class: ClearChatAction

Defined in: [WAProto/index.d.ts:30505](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30505)

Represents a ClearChatAction.

## Implements

- [`IClearChatAction`](../interfaces/IClearChatAction.md)

## Constructors

### new ClearChatAction()

> **new ClearChatAction**(`properties`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:30511](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30511)

Constructs a new ClearChatAction.

#### Parameters

##### properties?

[`IClearChatAction`](../interfaces/IClearChatAction.md)

Properties to set

#### Returns

[`ClearChatAction`](ClearChatAction.md)

## Properties

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:30514](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30514)

ClearChatAction messageRange.

#### Implementation of

[`IClearChatAction`](../interfaces/IClearChatAction.md).[`messageRange`](../interfaces/IClearChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30584](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30584)

Converts this ClearChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:30521](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30521)

Creates a new ClearChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IClearChatAction`](../interfaces/IClearChatAction.md)

Properties to set

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:30547](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30547)

Decodes a ClearChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:30556](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30556)

Decodes a ClearChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30529](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30529)

Encodes the specified ClearChatAction message. Does not implicitly [verify](ClearChatAction.md#verify) messages.

#### Parameters

##### message

[`IClearChatAction`](../interfaces/IClearChatAction.md)

ClearChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30537](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30537)

Encodes the specified ClearChatAction message, length delimited. Does not implicitly [verify](ClearChatAction.md#verify) messages.

#### Parameters

##### message

[`IClearChatAction`](../interfaces/IClearChatAction.md)

ClearChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:30570](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30570)

Creates a ClearChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30578)

Creates a plain object from a ClearChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30563](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30563)

Verifies a ClearChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
