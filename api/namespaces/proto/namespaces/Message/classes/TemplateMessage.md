# Class: TemplateMessage

Defined in: [WAProto/index.d.ts:22572](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22572)

Represents a TemplateMessage.

## Implements

- [`ITemplateMessage`](../interfaces/ITemplateMessage.md)

## Constructors

### new TemplateMessage()

> **new TemplateMessage**(`properties`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:22578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22578)

Constructs a new TemplateMessage.

#### Parameters

##### properties?

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

Properties to set

#### Returns

[`TemplateMessage`](TemplateMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:22581](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22581)

TemplateMessage contextInfo.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`contextInfo`](../interfaces/ITemplateMessage.md#contextinfo)

***

### format?

> `optional` **format**: `"hydratedFourRowTemplate"` \| `"fourRowTemplate"` \| `"interactiveMessageTemplate"`

Defined in: [WAProto/index.d.ts:22599](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22599)

TemplateMessage format.

***

### fourRowTemplate?

> `optional` **fourRowTemplate**: `null` \| [`IFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:22590](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22590)

TemplateMessage fourRowTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`fourRowTemplate`](../interfaces/ITemplateMessage.md#fourrowtemplate)

***

### hydratedFourRowTemplate?

> `optional` **hydratedFourRowTemplate**: `null` \| [`IHydratedFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IHydratedFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:22593](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22593)

TemplateMessage hydratedFourRowTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`hydratedFourRowTemplate`](../interfaces/ITemplateMessage.md#hydratedfourrowtemplate)

***

### hydratedTemplate?

> `optional` **hydratedTemplate**: `null` \| [`IHydratedFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IHydratedFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:22584](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22584)

TemplateMessage hydratedTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`hydratedTemplate`](../interfaces/ITemplateMessage.md#hydratedtemplate)

***

### interactiveMessageTemplate?

> `optional` **interactiveMessageTemplate**: `null` \| [`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

Defined in: [WAProto/index.d.ts:22596](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22596)

TemplateMessage interactiveMessageTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`interactiveMessageTemplate`](../interfaces/ITemplateMessage.md#interactivemessagetemplate)

***

### templateId

> **templateId**: `string`

Defined in: [WAProto/index.d.ts:22587](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22587)

TemplateMessage templateId.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`templateId`](../interfaces/ITemplateMessage.md#templateid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22669](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22669)

Converts this TemplateMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:22606](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22606)

Creates a new TemplateMessage instance using the specified properties.

#### Parameters

##### properties?

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

Properties to set

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:22632](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22632)

Decodes a TemplateMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:22641](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22641)

Decodes a TemplateMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22614](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22614)

Encodes the specified TemplateMessage message. Does not implicitly [verify](TemplateMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

TemplateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22622](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22622)

Encodes the specified TemplateMessage message, length delimited. Does not implicitly [verify](TemplateMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

TemplateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:22655](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22655)

Creates a TemplateMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:22663](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22663)

Creates a plain object from a TemplateMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22648](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L22648)

Verifies a TemplateMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
