# Class: ButtonsMessage

Defined in: [WAProto/index.d.ts:11244](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11244)

Represents a ButtonsMessage.

## Implements

- [`IButtonsMessage`](../interfaces/IButtonsMessage.md)

## Constructors

### new ButtonsMessage()

> **new ButtonsMessage**(`properties`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:11250](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11250)

Constructs a new ButtonsMessage.

#### Parameters

##### properties?

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

Properties to set

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

## Properties

### buttons

> **buttons**: [`IButton`](../namespaces/ButtonsMessage/interfaces/IButton.md)[]

Defined in: [WAProto/index.d.ts:11262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11262)

ButtonsMessage buttons.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`buttons`](../interfaces/IButtonsMessage.md#buttons)

***

### contentText

> **contentText**: `string`

Defined in: [WAProto/index.d.ts:11253](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11253)

ButtonsMessage contentText.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`contentText`](../interfaces/IButtonsMessage.md#contenttext)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:11259](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11259)

ButtonsMessage contextInfo.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`contextInfo`](../interfaces/IButtonsMessage.md#contextinfo)

***

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:11271](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11271)

ButtonsMessage documentMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`documentMessage`](../interfaces/IButtonsMessage.md#documentmessage)

***

### footerText

> **footerText**: `string`

Defined in: [WAProto/index.d.ts:11256](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11256)

ButtonsMessage footerText.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`footerText`](../interfaces/IButtonsMessage.md#footertext)

***

### header?

> `optional` **header**: `"text"` \| `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"`

Defined in: [WAProto/index.d.ts:11283](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11283)

ButtonsMessage header.

***

### headerType

> **headerType**: [`HeaderType`](../namespaces/ButtonsMessage/enumerations/HeaderType.md)

Defined in: [WAProto/index.d.ts:11265](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11265)

ButtonsMessage headerType.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`headerType`](../interfaces/IButtonsMessage.md#headertype)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:11274](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11274)

ButtonsMessage imageMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`imageMessage`](../interfaces/IButtonsMessage.md#imagemessage)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:11280](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11280)

ButtonsMessage locationMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`locationMessage`](../interfaces/IButtonsMessage.md#locationmessage)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11268](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11268)

ButtonsMessage text.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`text`](../interfaces/IButtonsMessage.md#text)

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:11277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11277)

ButtonsMessage videoMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`videoMessage`](../interfaces/IButtonsMessage.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11353](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11353)

Converts this ButtonsMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:11290](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11290)

Creates a new ButtonsMessage instance using the specified properties.

#### Parameters

##### properties?

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

Properties to set

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:11316](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11316)

Decodes a ButtonsMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:11325](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11325)

Decodes a ButtonsMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11298](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11298)

Encodes the specified ButtonsMessage message. Does not implicitly [verify](ButtonsMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

ButtonsMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11306](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11306)

Encodes the specified ButtonsMessage message, length delimited. Does not implicitly [verify](ButtonsMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

ButtonsMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:11339](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11339)

Creates a ButtonsMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11347](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11347)

Creates a plain object from a ButtonsMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11332](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11332)

Verifies a ButtonsMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
