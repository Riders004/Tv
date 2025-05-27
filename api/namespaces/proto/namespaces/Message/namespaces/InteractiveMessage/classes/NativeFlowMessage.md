# Class: NativeFlowMessage

Defined in: [WAProto/index.d.ts:16185](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16185)

Represents a NativeFlowMessage.

## Implements

- [`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

## Constructors

### new NativeFlowMessage()

> **new NativeFlowMessage**(`properties`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:16191](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16191)

Constructs a new NativeFlowMessage.

#### Parameters

##### properties?

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

Properties to set

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

## Properties

### buttons

> **buttons**: [`INativeFlowButton`](../namespaces/NativeFlowMessage/interfaces/INativeFlowButton.md)[]

Defined in: [WAProto/index.d.ts:16194](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16194)

NativeFlowMessage buttons.

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`buttons`](../interfaces/INativeFlowMessage.md#buttons)

***

### messageParamsJson

> **messageParamsJson**: `string`

Defined in: [WAProto/index.d.ts:16197](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16197)

NativeFlowMessage messageParamsJson.

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`messageParamsJson`](../interfaces/INativeFlowMessage.md#messageparamsjson)

***

### messageVersion

> **messageVersion**: `number`

Defined in: [WAProto/index.d.ts:16200](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16200)

NativeFlowMessage messageVersion.

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`messageVersion`](../interfaces/INativeFlowMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16270](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16270)

Converts this NativeFlowMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:16207](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16207)

Creates a new NativeFlowMessage instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

Properties to set

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:16233](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16233)

Decodes a NativeFlowMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:16242](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16242)

Decodes a NativeFlowMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16215](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16215)

Encodes the specified NativeFlowMessage message. Does not implicitly [verify](NativeFlowMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

NativeFlowMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16223](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16223)

Encodes the specified NativeFlowMessage message, length delimited. Does not implicitly [verify](NativeFlowMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

NativeFlowMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:16256](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16256)

Creates a NativeFlowMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16264](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16264)

Creates a plain object from a NativeFlowMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16249](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16249)

Verifies a NativeFlowMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
