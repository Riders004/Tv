# Class: InteractiveResponseMessage

Defined in: [WAProto/index.d.ts:16500](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16500)

Represents an InteractiveResponseMessage.

## Implements

- [`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

## Constructors

### new InteractiveResponseMessage()

> **new InteractiveResponseMessage**(`properties`?): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:16506](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16506)

Constructs a new InteractiveResponseMessage.

#### Parameters

##### properties?

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

Properties to set

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

## Properties

### body?

> `optional` **body**: `null` \| [`IBody`](../namespaces/InteractiveResponseMessage/interfaces/IBody.md)

Defined in: [WAProto/index.d.ts:16509](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16509)

InteractiveResponseMessage body.

#### Implementation of

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md).[`body`](../interfaces/IInteractiveResponseMessage.md#body)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:16512](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16512)

InteractiveResponseMessage contextInfo.

#### Implementation of

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md).[`contextInfo`](../interfaces/IInteractiveResponseMessage.md#contextinfo)

***

### interactiveResponseMessage?

> `optional` **interactiveResponseMessage**: `"nativeFlowResponseMessage"`

Defined in: [WAProto/index.d.ts:16518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16518)

InteractiveResponseMessage interactiveResponseMessage.

***

### nativeFlowResponseMessage?

> `optional` **nativeFlowResponseMessage**: `null` \| [`INativeFlowResponseMessage`](../namespaces/InteractiveResponseMessage/interfaces/INativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:16515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16515)

InteractiveResponseMessage nativeFlowResponseMessage.

#### Implementation of

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md).[`nativeFlowResponseMessage`](../interfaces/IInteractiveResponseMessage.md#nativeflowresponsemessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16588](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16588)

Converts this InteractiveResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:16525](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16525)

Creates a new InteractiveResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

Properties to set

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

InteractiveResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:16551](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16551)

Decodes an InteractiveResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

InteractiveResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:16560](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16560)

Decodes an InteractiveResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

InteractiveResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16533](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16533)

Encodes the specified InteractiveResponseMessage message. Does not implicitly [verify](InteractiveResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

InteractiveResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16541)

Encodes the specified InteractiveResponseMessage message, length delimited. Does not implicitly [verify](InteractiveResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

InteractiveResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:16574](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16574)

Creates an InteractiveResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

InteractiveResponseMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16582](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16582)

Creates a plain object from an InteractiveResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

InteractiveResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16567)

Verifies an InteractiveResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
