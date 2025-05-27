# Class: NativeFlowButton

Defined in: [WAProto/index.d.ts:16286](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16286)

Represents a NativeFlowButton.

## Implements

- [`INativeFlowButton`](../interfaces/INativeFlowButton.md)

## Constructors

### new NativeFlowButton()

> **new NativeFlowButton**(`properties`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:16292](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16292)

Constructs a new NativeFlowButton.

#### Parameters

##### properties?

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

Properties to set

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

## Properties

### buttonParamsJson

> **buttonParamsJson**: `string`

Defined in: [WAProto/index.d.ts:16298](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16298)

NativeFlowButton buttonParamsJson.

#### Implementation of

[`INativeFlowButton`](../interfaces/INativeFlowButton.md).[`buttonParamsJson`](../interfaces/INativeFlowButton.md#buttonparamsjson)

***

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:16295](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16295)

NativeFlowButton name.

#### Implementation of

[`INativeFlowButton`](../interfaces/INativeFlowButton.md).[`name`](../interfaces/INativeFlowButton.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16368](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16368)

Converts this NativeFlowButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:16305](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16305)

Creates a new NativeFlowButton instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

Properties to set

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:16331](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16331)

Decodes a NativeFlowButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:16340](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16340)

Decodes a NativeFlowButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16313](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16313)

Encodes the specified NativeFlowButton message. Does not implicitly [verify](NativeFlowButton.md#verify) messages.

#### Parameters

##### message

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

NativeFlowButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16321](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16321)

Encodes the specified NativeFlowButton message, length delimited. Does not implicitly [verify](NativeFlowButton.md#verify) messages.

#### Parameters

##### message

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

NativeFlowButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:16354](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16354)

Creates a NativeFlowButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16362](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16362)

Creates a plain object from a NativeFlowButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16347](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16347)

Verifies a NativeFlowButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
