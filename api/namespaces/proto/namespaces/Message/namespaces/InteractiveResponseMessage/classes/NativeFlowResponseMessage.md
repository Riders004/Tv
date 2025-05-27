# Class: NativeFlowResponseMessage

Defined in: [WAProto/index.d.ts:16712](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16712)

Represents a NativeFlowResponseMessage.

## Implements

- [`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

## Constructors

### new NativeFlowResponseMessage()

> **new NativeFlowResponseMessage**(`properties`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:16718](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16718)

Constructs a new NativeFlowResponseMessage.

#### Parameters

##### properties?

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

Properties to set

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

## Properties

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:16721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16721)

NativeFlowResponseMessage name.

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`name`](../interfaces/INativeFlowResponseMessage.md#name)

***

### paramsJson

> **paramsJson**: `string`

Defined in: [WAProto/index.d.ts:16724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16724)

NativeFlowResponseMessage paramsJson.

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`paramsJson`](../interfaces/INativeFlowResponseMessage.md#paramsjson)

***

### version

> **version**: `number`

Defined in: [WAProto/index.d.ts:16727](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16727)

NativeFlowResponseMessage version.

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`version`](../interfaces/INativeFlowResponseMessage.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16797](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16797)

Converts this NativeFlowResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:16734](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16734)

Creates a new NativeFlowResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

Properties to set

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:16760](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16760)

Decodes a NativeFlowResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:16769](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16769)

Decodes a NativeFlowResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16742](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16742)

Encodes the specified NativeFlowResponseMessage message. Does not implicitly [verify](NativeFlowResponseMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

NativeFlowResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16750](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16750)

Encodes the specified NativeFlowResponseMessage message, length delimited. Does not implicitly [verify](NativeFlowResponseMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

NativeFlowResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:16783](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16783)

Creates a NativeFlowResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16791](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16791)

Creates a plain object from a NativeFlowResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16776](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16776)

Verifies a NativeFlowResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
