# Class: ButtonsResponseMessage

Defined in: [WAProto/index.d.ts:11691](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11691)

Represents a ButtonsResponseMessage.

## Implements

- [`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

## Constructors

### new ButtonsResponseMessage()

> **new ButtonsResponseMessage**(`properties`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:11697](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11697)

Constructs a new ButtonsResponseMessage.

#### Parameters

##### properties?

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

Properties to set

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:11703](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11703)

ButtonsResponseMessage contextInfo.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`contextInfo`](../interfaces/IButtonsResponseMessage.md#contextinfo)

***

### response?

> `optional` **response**: `"selectedDisplayText"`

Defined in: [WAProto/index.d.ts:11712](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11712)

ButtonsResponseMessage response.

***

### selectedButtonId

> **selectedButtonId**: `string`

Defined in: [WAProto/index.d.ts:11700](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11700)

ButtonsResponseMessage selectedButtonId.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`selectedButtonId`](../interfaces/IButtonsResponseMessage.md#selectedbuttonid)

***

### selectedDisplayText?

> `optional` **selectedDisplayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11709](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11709)

ButtonsResponseMessage selectedDisplayText.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`selectedDisplayText`](../interfaces/IButtonsResponseMessage.md#selecteddisplaytext)

***

### type

> **type**: [`Type`](../namespaces/ButtonsResponseMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:11706](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11706)

ButtonsResponseMessage type.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`type`](../interfaces/IButtonsResponseMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11782](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11782)

Converts this ButtonsResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:11719](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11719)

Creates a new ButtonsResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

Properties to set

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:11745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11745)

Decodes a ButtonsResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:11754](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11754)

Decodes a ButtonsResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11727](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11727)

Encodes the specified ButtonsResponseMessage message. Does not implicitly [verify](ButtonsResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

ButtonsResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11735](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11735)

Encodes the specified ButtonsResponseMessage message, length delimited. Does not implicitly [verify](ButtonsResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

ButtonsResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:11768](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11768)

Creates a ButtonsResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11776](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11776)

Creates a plain object from a ButtonsResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11761](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11761)

Verifies a ButtonsResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
