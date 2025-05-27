# Class: TemplateButtonReplyMessage

Defined in: [WAProto/index.d.ts:22455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22455)

Represents a TemplateButtonReplyMessage.

## Implements

- [`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

## Constructors

### new TemplateButtonReplyMessage()

> **new TemplateButtonReplyMessage**(`properties`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:22461](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22461)

Constructs a new TemplateButtonReplyMessage.

#### Parameters

##### properties?

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

Properties to set

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:22470](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22470)

TemplateButtonReplyMessage contextInfo.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`contextInfo`](../interfaces/ITemplateButtonReplyMessage.md#contextinfo)

***

### selectedCarouselCardIndex

> **selectedCarouselCardIndex**: `number`

Defined in: [WAProto/index.d.ts:22476](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22476)

TemplateButtonReplyMessage selectedCarouselCardIndex.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedCarouselCardIndex`](../interfaces/ITemplateButtonReplyMessage.md#selectedcarouselcardindex)

***

### selectedDisplayText

> **selectedDisplayText**: `string`

Defined in: [WAProto/index.d.ts:22467](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22467)

TemplateButtonReplyMessage selectedDisplayText.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedDisplayText`](../interfaces/ITemplateButtonReplyMessage.md#selecteddisplaytext)

***

### selectedId

> **selectedId**: `string`

Defined in: [WAProto/index.d.ts:22464](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22464)

TemplateButtonReplyMessage selectedId.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedId`](../interfaces/ITemplateButtonReplyMessage.md#selectedid)

***

### selectedIndex

> **selectedIndex**: `number`

Defined in: [WAProto/index.d.ts:22473](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22473)

TemplateButtonReplyMessage selectedIndex.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedIndex`](../interfaces/ITemplateButtonReplyMessage.md#selectedindex)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22546](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22546)

Converts this TemplateButtonReplyMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:22483](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22483)

Creates a new TemplateButtonReplyMessage instance using the specified properties.

#### Parameters

##### properties?

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

Properties to set

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:22509](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22509)

Decodes a TemplateButtonReplyMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:22518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22518)

Decodes a TemplateButtonReplyMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22491](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22491)

Encodes the specified TemplateButtonReplyMessage message. Does not implicitly [verify](TemplateButtonReplyMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

TemplateButtonReplyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22499](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22499)

Encodes the specified TemplateButtonReplyMessage message, length delimited. Does not implicitly [verify](TemplateButtonReplyMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

TemplateButtonReplyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:22532](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22532)

Creates a TemplateButtonReplyMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:22540](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22540)

Creates a plain object from a TemplateButtonReplyMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22525](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22525)

Verifies a TemplateButtonReplyMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
