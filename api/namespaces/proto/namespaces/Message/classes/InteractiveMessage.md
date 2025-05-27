# Class: InteractiveMessage

Defined in: [WAProto/index.d.ts:15550](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15550)

Represents an InteractiveMessage.

## Implements

- [`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

## Constructors

### new InteractiveMessage()

> **new InteractiveMessage**(`properties`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:15556](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15556)

Constructs a new InteractiveMessage.

#### Parameters

##### properties?

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

Properties to set

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

## Properties

### body?

> `optional` **body**: `null` \| [`IBody`](../namespaces/InteractiveMessage/interfaces/IBody.md)

Defined in: [WAProto/index.d.ts:15562](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15562)

InteractiveMessage body.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`body`](../interfaces/IInteractiveMessage.md#body)

***

### carouselMessage?

> `optional` **carouselMessage**: `null` \| [`ICarouselMessage`](../namespaces/InteractiveMessage/interfaces/ICarouselMessage.md)

Defined in: [WAProto/index.d.ts:15580](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15580)

InteractiveMessage carouselMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`carouselMessage`](../interfaces/IInteractiveMessage.md#carouselmessage)

***

### collectionMessage?

> `optional` **collectionMessage**: `null` \| [`ICollectionMessage`](../namespaces/InteractiveMessage/interfaces/ICollectionMessage.md)

Defined in: [WAProto/index.d.ts:15574](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15574)

InteractiveMessage collectionMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`collectionMessage`](../interfaces/IInteractiveMessage.md#collectionmessage)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:15568](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15568)

InteractiveMessage contextInfo.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`contextInfo`](../interfaces/IInteractiveMessage.md#contextinfo)

***

### footer?

> `optional` **footer**: `null` \| [`IFooter`](../namespaces/InteractiveMessage/interfaces/IFooter.md)

Defined in: [WAProto/index.d.ts:15565](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15565)

InteractiveMessage footer.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`footer`](../interfaces/IInteractiveMessage.md#footer)

***

### header?

> `optional` **header**: `null` \| [`IHeader`](../namespaces/InteractiveMessage/interfaces/IHeader.md)

Defined in: [WAProto/index.d.ts:15559](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15559)

InteractiveMessage header.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`header`](../interfaces/IInteractiveMessage.md#header)

***

### interactiveMessage?

> `optional` **interactiveMessage**: `"shopStorefrontMessage"` \| `"collectionMessage"` \| `"nativeFlowMessage"` \| `"carouselMessage"`

Defined in: [WAProto/index.d.ts:15583](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15583)

InteractiveMessage interactiveMessage.

***

### nativeFlowMessage?

> `optional` **nativeFlowMessage**: `null` \| [`INativeFlowMessage`](../namespaces/InteractiveMessage/interfaces/INativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:15577](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15577)

InteractiveMessage nativeFlowMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`nativeFlowMessage`](../interfaces/IInteractiveMessage.md#nativeflowmessage)

***

### shopStorefrontMessage?

> `optional` **shopStorefrontMessage**: `null` \| [`IShopMessage`](../namespaces/InteractiveMessage/interfaces/IShopMessage.md)

Defined in: [WAProto/index.d.ts:15571](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15571)

InteractiveMessage shopStorefrontMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`shopStorefrontMessage`](../interfaces/IInteractiveMessage.md#shopstorefrontmessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15653](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15653)

Converts this InteractiveMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:15590](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15590)

Creates a new InteractiveMessage instance using the specified properties.

#### Parameters

##### properties?

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

Properties to set

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:15616](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15616)

Decodes an InteractiveMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:15625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15625)

Decodes an InteractiveMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15598](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15598)

Encodes the specified InteractiveMessage message. Does not implicitly [verify](InteractiveMessage.md#verify) messages.

#### Parameters

##### message

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

InteractiveMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15606](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15606)

Encodes the specified InteractiveMessage message, length delimited. Does not implicitly [verify](InteractiveMessage.md#verify) messages.

#### Parameters

##### message

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

InteractiveMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:15639](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15639)

Creates an InteractiveMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:15647](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15647)

Creates a plain object from an InteractiveMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15632](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15632)

Verifies an InteractiveMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
