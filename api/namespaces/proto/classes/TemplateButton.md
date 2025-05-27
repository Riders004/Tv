# Class: TemplateButton

Defined in: [WAProto/index.d.ts:35102](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35102)

Represents a TemplateButton.

## Implements

- [`ITemplateButton`](../interfaces/ITemplateButton.md)

## Constructors

### new TemplateButton()

> **new TemplateButton**(`properties`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:35108](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35108)

Constructs a new TemplateButton.

#### Parameters

##### properties?

[`ITemplateButton`](../interfaces/ITemplateButton.md)

Properties to set

#### Returns

[`TemplateButton`](TemplateButton.md)

## Properties

### button?

> `optional` **button**: `"quickReplyButton"` \| `"urlButton"` \| `"callButton"`

Defined in: [WAProto/index.d.ts:35123](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35123)

TemplateButton button.

***

### callButton?

> `optional` **callButton**: `null` \| [`ICallButton`](../namespaces/TemplateButton/interfaces/ICallButton.md)

Defined in: [WAProto/index.d.ts:35120](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35120)

TemplateButton callButton.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`callButton`](../interfaces/ITemplateButton.md#callbutton)

***

### index

> **index**: `number`

Defined in: [WAProto/index.d.ts:35111](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35111)

TemplateButton index.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`index`](../interfaces/ITemplateButton.md#index)

***

### quickReplyButton?

> `optional` **quickReplyButton**: `null` \| [`IQuickReplyButton`](../namespaces/TemplateButton/interfaces/IQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:35114](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35114)

TemplateButton quickReplyButton.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`quickReplyButton`](../interfaces/ITemplateButton.md#quickreplybutton)

***

### urlButton?

> `optional` **urlButton**: `null` \| [`IURLButton`](../namespaces/TemplateButton/interfaces/IURLButton.md)

Defined in: [WAProto/index.d.ts:35117](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35117)

TemplateButton urlButton.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`urlButton`](../interfaces/ITemplateButton.md#urlbutton)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35193](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35193)

Converts this TemplateButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:35130](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35130)

Creates a new TemplateButton instance using the specified properties.

#### Parameters

##### properties?

[`ITemplateButton`](../interfaces/ITemplateButton.md)

Properties to set

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:35156](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35156)

Decodes a TemplateButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:35165](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35165)

Decodes a TemplateButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35138](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35138)

Encodes the specified TemplateButton message. Does not implicitly [verify](TemplateButton.md#verify) messages.

#### Parameters

##### message

[`ITemplateButton`](../interfaces/ITemplateButton.md)

TemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35146](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35146)

Encodes the specified TemplateButton message, length delimited. Does not implicitly [verify](TemplateButton.md#verify) messages.

#### Parameters

##### message

[`ITemplateButton`](../interfaces/ITemplateButton.md)

TemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:35179](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35179)

Creates a TemplateButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35187](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35187)

Creates a plain object from a TemplateButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`TemplateButton`](TemplateButton.md)

TemplateButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35172](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35172)

Verifies a TemplateButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
