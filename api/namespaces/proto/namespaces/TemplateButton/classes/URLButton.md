# Class: URLButton

Defined in: [WAProto/index.d.ts:35401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35401)

Represents a URLButton.

## Implements

- [`IURLButton`](../interfaces/IURLButton.md)

## Constructors

### new URLButton()

> **new URLButton**(`properties`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:35407](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35407)

Constructs a new URLButton.

#### Parameters

##### properties?

[`IURLButton`](../interfaces/IURLButton.md)

Properties to set

#### Returns

[`URLButton`](URLButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:35410](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35410)

URLButton displayText.

#### Implementation of

[`IURLButton`](../interfaces/IURLButton.md).[`displayText`](../interfaces/IURLButton.md#displaytext)

***

### url?

> `optional` **url**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:35413](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35413)

URLButton url.

#### Implementation of

[`IURLButton`](../interfaces/IURLButton.md).[`url`](../interfaces/IURLButton.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35483](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35483)

Converts this URLButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:35420](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35420)

Creates a new URLButton instance using the specified properties.

#### Parameters

##### properties?

[`IURLButton`](../interfaces/IURLButton.md)

Properties to set

#### Returns

[`URLButton`](URLButton.md)

URLButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:35446](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35446)

Decodes a URLButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`URLButton`](URLButton.md)

URLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:35455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35455)

Decodes a URLButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`URLButton`](URLButton.md)

URLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35428](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35428)

Encodes the specified URLButton message. Does not implicitly [verify](URLButton.md#verify) messages.

#### Parameters

##### message

[`IURLButton`](../interfaces/IURLButton.md)

URLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35436](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35436)

Encodes the specified URLButton message, length delimited. Does not implicitly [verify](URLButton.md#verify) messages.

#### Parameters

##### message

[`IURLButton`](../interfaces/IURLButton.md)

URLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:35469](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35469)

Creates a URLButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`URLButton`](URLButton.md)

URLButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35477](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35477)

Creates a plain object from a URLButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`URLButton`](URLButton.md)

URLButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35462](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35462)

Verifies a URLButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
