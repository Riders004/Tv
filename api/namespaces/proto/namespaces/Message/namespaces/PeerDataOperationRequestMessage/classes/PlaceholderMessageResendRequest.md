# Class: PlaceholderMessageResendRequest

Defined in: [WAProto/index.d.ts:19067](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19067)

Represents a PlaceholderMessageResendRequest.

## Implements

- [`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

## Constructors

### new PlaceholderMessageResendRequest()

> **new PlaceholderMessageResendRequest**(`properties`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:19073](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19073)

Constructs a new PlaceholderMessageResendRequest.

#### Parameters

##### properties?

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

Properties to set

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

## Properties

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../../../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:19076](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19076)

PlaceholderMessageResendRequest messageKey.

#### Implementation of

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md).[`messageKey`](../interfaces/IPlaceholderMessageResendRequest.md#messagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19146](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19146)

Converts this PlaceholderMessageResendRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:19083](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19083)

Creates a new PlaceholderMessageResendRequest instance using the specified properties.

#### Parameters

##### properties?

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

Properties to set

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:19109](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19109)

Decodes a PlaceholderMessageResendRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:19118](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19118)

Decodes a PlaceholderMessageResendRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19091](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19091)

Encodes the specified PlaceholderMessageResendRequest message. Does not implicitly [verify](PlaceholderMessageResendRequest.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19099](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19099)

Encodes the specified PlaceholderMessageResendRequest message, length delimited. Does not implicitly [verify](PlaceholderMessageResendRequest.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:19132](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19132)

Creates a PlaceholderMessageResendRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:19140](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19140)

Creates a plain object from a PlaceholderMessageResendRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19125](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19125)

Verifies a PlaceholderMessageResendRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
