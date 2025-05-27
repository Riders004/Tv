# Class: HydratedTemplateButton

Defined in: [WAProto/index.d.ts:7754](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7754)

Represents a HydratedTemplateButton.

## Implements

- [`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

## Constructors

### new HydratedTemplateButton()

> **new HydratedTemplateButton**(`properties`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:7760](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7760)

Constructs a new HydratedTemplateButton.

#### Parameters

##### properties?

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

Properties to set

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

## Properties

### callButton?

> `optional` **callButton**: `null` \| [`IHydratedCallButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedCallButton.md)

Defined in: [WAProto/index.d.ts:7772](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7772)

HydratedTemplateButton callButton.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`callButton`](../interfaces/IHydratedTemplateButton.md#callbutton)

***

### hydratedButton?

> `optional` **hydratedButton**: `"quickReplyButton"` \| `"urlButton"` \| `"callButton"`

Defined in: [WAProto/index.d.ts:7775](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7775)

HydratedTemplateButton hydratedButton.

***

### index

> **index**: `number`

Defined in: [WAProto/index.d.ts:7763](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7763)

HydratedTemplateButton index.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`index`](../interfaces/IHydratedTemplateButton.md#index)

***

### quickReplyButton?

> `optional` **quickReplyButton**: `null` \| [`IHydratedQuickReplyButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:7766](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7766)

HydratedTemplateButton quickReplyButton.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`quickReplyButton`](../interfaces/IHydratedTemplateButton.md#quickreplybutton)

***

### urlButton?

> `optional` **urlButton**: `null` \| [`IHydratedURLButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedURLButton.md)

Defined in: [WAProto/index.d.ts:7769](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7769)

HydratedTemplateButton urlButton.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`urlButton`](../interfaces/IHydratedTemplateButton.md#urlbutton)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7845](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7845)

Converts this HydratedTemplateButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:7782](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7782)

Creates a new HydratedTemplateButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

Properties to set

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:7808](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7808)

Decodes a HydratedTemplateButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:7817](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7817)

Decodes a HydratedTemplateButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7790](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7790)

Encodes the specified HydratedTemplateButton message. Does not implicitly [verify](HydratedTemplateButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

HydratedTemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7798](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7798)

Encodes the specified HydratedTemplateButton message, length delimited. Does not implicitly [verify](HydratedTemplateButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

HydratedTemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:7831](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7831)

Creates a HydratedTemplateButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:7839](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7839)

Creates a plain object from a HydratedTemplateButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7824](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7824)

Verifies a HydratedTemplateButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
