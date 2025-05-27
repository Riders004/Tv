# Class: PlaceholderMessageResendResponse

Defined in: [WAProto/index.d.ts:19819](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19819)

Represents a PlaceholderMessageResendResponse.

## Implements

- [`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

## Constructors

### new PlaceholderMessageResendResponse()

> **new PlaceholderMessageResendResponse**(`properties`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:19825](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19825)

Constructs a new PlaceholderMessageResendResponse.

#### Parameters

##### properties?

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

Properties to set

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

## Properties

### webMessageInfoBytes

> **webMessageInfoBytes**: `Uint8Array`

Defined in: [WAProto/index.d.ts:19828](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19828)

PlaceholderMessageResendResponse webMessageInfoBytes.

#### Implementation of

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md).[`webMessageInfoBytes`](../interfaces/IPlaceholderMessageResendResponse.md#webmessageinfobytes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19898](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19898)

Converts this PlaceholderMessageResendResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:19835](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19835)

Creates a new PlaceholderMessageResendResponse instance using the specified properties.

#### Parameters

##### properties?

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

Properties to set

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:19861](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19861)

Decodes a PlaceholderMessageResendResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:19870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19870)

Decodes a PlaceholderMessageResendResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19843](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19843)

Encodes the specified PlaceholderMessageResendResponse message. Does not implicitly [verify](PlaceholderMessageResendResponse.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19851](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19851)

Encodes the specified PlaceholderMessageResendResponse message, length delimited. Does not implicitly [verify](PlaceholderMessageResendResponse.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:19884](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19884)

Creates a PlaceholderMessageResendResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:19892](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19892)

Creates a plain object from a PlaceholderMessageResendResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19877](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L19877)

Verifies a PlaceholderMessageResendResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
