# Class: StickerAction

Defined in: [WAProto/index.d.ts:33592](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33592)

Represents a StickerAction.

## Implements

- [`IStickerAction`](../interfaces/IStickerAction.md)

## Constructors

### new StickerAction()

> **new StickerAction**(`properties`?): [`StickerAction`](StickerAction.md)

Defined in: [WAProto/index.d.ts:33598](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33598)

Constructs a new StickerAction.

#### Parameters

##### properties?

[`IStickerAction`](../interfaces/IStickerAction.md)

Properties to set

#### Returns

[`StickerAction`](StickerAction.md)

## Properties

### deviceIdHint

> **deviceIdHint**: `number`

Defined in: [WAProto/index.d.ts:33628](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33628)

StickerAction deviceIdHint.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`deviceIdHint`](../interfaces/IStickerAction.md#deviceidhint)

***

### directPath

> **directPath**: `string`

Defined in: [WAProto/index.d.ts:33619](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33619)

StickerAction directPath.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`directPath`](../interfaces/IStickerAction.md#directpath)

***

### fileEncSha256

> **fileEncSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:33604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33604)

StickerAction fileEncSha256.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`fileEncSha256`](../interfaces/IStickerAction.md#fileencsha256)

***

### fileLength

> **fileLength**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:33622](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33622)

StickerAction fileLength.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`fileLength`](../interfaces/IStickerAction.md#filelength)

***

### height

> **height**: `number`

Defined in: [WAProto/index.d.ts:33613](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33613)

StickerAction height.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`height`](../interfaces/IStickerAction.md#height)

***

### isFavorite

> **isFavorite**: `boolean`

Defined in: [WAProto/index.d.ts:33625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33625)

StickerAction isFavorite.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`isFavorite`](../interfaces/IStickerAction.md#isfavorite)

***

### mediaKey

> **mediaKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:33607](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33607)

StickerAction mediaKey.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`mediaKey`](../interfaces/IStickerAction.md#mediakey)

***

### mimetype

> **mimetype**: `string`

Defined in: [WAProto/index.d.ts:33610](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33610)

StickerAction mimetype.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`mimetype`](../interfaces/IStickerAction.md#mimetype)

***

### url

> **url**: `string`

Defined in: [WAProto/index.d.ts:33601](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33601)

StickerAction url.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`url`](../interfaces/IStickerAction.md#url)

***

### width

> **width**: `number`

Defined in: [WAProto/index.d.ts:33616](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33616)

StickerAction width.

#### Implementation of

[`IStickerAction`](../interfaces/IStickerAction.md).[`width`](../interfaces/IStickerAction.md#width)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33698](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33698)

Converts this StickerAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StickerAction`](StickerAction.md)

Defined in: [WAProto/index.d.ts:33635](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33635)

Creates a new StickerAction instance using the specified properties.

#### Parameters

##### properties?

[`IStickerAction`](../interfaces/IStickerAction.md)

Properties to set

#### Returns

[`StickerAction`](StickerAction.md)

StickerAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StickerAction`](StickerAction.md)

Defined in: [WAProto/index.d.ts:33661](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33661)

Decodes a StickerAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StickerAction`](StickerAction.md)

StickerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StickerAction`](StickerAction.md)

Defined in: [WAProto/index.d.ts:33670](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33670)

Decodes a StickerAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StickerAction`](StickerAction.md)

StickerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33643](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33643)

Encodes the specified StickerAction message. Does not implicitly [verify](StickerAction.md#verify) messages.

#### Parameters

##### message

[`IStickerAction`](../interfaces/IStickerAction.md)

StickerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33651](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33651)

Encodes the specified StickerAction message, length delimited. Does not implicitly [verify](StickerAction.md#verify) messages.

#### Parameters

##### message

[`IStickerAction`](../interfaces/IStickerAction.md)

StickerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StickerAction`](StickerAction.md)

Defined in: [WAProto/index.d.ts:33684](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33684)

Creates a StickerAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StickerAction`](StickerAction.md)

StickerAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33692)

Creates a plain object from a StickerAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`StickerAction`](StickerAction.md)

StickerAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33677](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33677)

Verifies a StickerAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
