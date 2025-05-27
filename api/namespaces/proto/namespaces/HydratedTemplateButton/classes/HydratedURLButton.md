# Class: HydratedURLButton

Defined in: [WAProto/index.d.ts:8059](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8059)

Represents a HydratedURLButton.

## Implements

- [`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

## Constructors

### new HydratedURLButton()

> **new HydratedURLButton**(`properties`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:8065](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8065)

Constructs a new HydratedURLButton.

#### Parameters

##### properties?

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

Properties to set

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

## Properties

### consentedUsersUrl

> **consentedUsersUrl**: `string`

Defined in: [WAProto/index.d.ts:8074](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8074)

HydratedURLButton consentedUsersUrl.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`consentedUsersUrl`](../interfaces/IHydratedURLButton.md#consentedusersurl)

***

### displayText

> **displayText**: `string`

Defined in: [WAProto/index.d.ts:8068](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8068)

HydratedURLButton displayText.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`displayText`](../interfaces/IHydratedURLButton.md#displaytext)

***

### url

> **url**: `string`

Defined in: [WAProto/index.d.ts:8071](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8071)

HydratedURLButton url.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`url`](../interfaces/IHydratedURLButton.md#url)

***

### webviewPresentation

> **webviewPresentation**: [`WebviewPresentationType`](../namespaces/HydratedURLButton/enumerations/WebviewPresentationType.md)

Defined in: [WAProto/index.d.ts:8077](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8077)

HydratedURLButton webviewPresentation.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`webviewPresentation`](../interfaces/IHydratedURLButton.md#webviewpresentation)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8147](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8147)

Converts this HydratedURLButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:8084](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8084)

Creates a new HydratedURLButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

Properties to set

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:8110](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8110)

Decodes a HydratedURLButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:8119](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8119)

Decodes a HydratedURLButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8092)

Encodes the specified HydratedURLButton message. Does not implicitly [verify](HydratedURLButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

HydratedURLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8100](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8100)

Encodes the specified HydratedURLButton message, length delimited. Does not implicitly [verify](HydratedURLButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

HydratedURLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:8133](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8133)

Creates a HydratedURLButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8141)

Creates a plain object from a HydratedURLButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8126](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8126)

Verifies a HydratedURLButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
