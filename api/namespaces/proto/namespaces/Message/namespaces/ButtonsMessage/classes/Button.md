# Class: Button

Defined in: [WAProto/index.d.ts:11375](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11375)

Represents a Button.

## Implements

- [`IButton`](../interfaces/IButton.md)

## Constructors

### new Button()

> **new Button**(`properties`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:11381](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11381)

Constructs a new Button.

#### Parameters

##### properties?

[`IButton`](../interfaces/IButton.md)

Properties to set

#### Returns

[`Button`](Button.md)

## Properties

### buttonId

> **buttonId**: `string`

Defined in: [WAProto/index.d.ts:11384](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11384)

Button buttonId.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`buttonId`](../interfaces/IButton.md#buttonid)

***

### buttonText?

> `optional` **buttonText**: `null` \| [`IButtonText`](../namespaces/Button/interfaces/IButtonText.md)

Defined in: [WAProto/index.d.ts:11387](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11387)

Button buttonText.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`buttonText`](../interfaces/IButton.md#buttontext)

***

### nativeFlowInfo?

> `optional` **nativeFlowInfo**: `null` \| [`INativeFlowInfo`](../namespaces/Button/interfaces/INativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:11393](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11393)

Button nativeFlowInfo.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`nativeFlowInfo`](../interfaces/IButton.md#nativeflowinfo)

***

### type

> **type**: [`Type`](../namespaces/Button/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:11390](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11390)

Button type.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`type`](../interfaces/IButton.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11463](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11463)

Converts this Button to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:11400](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11400)

Creates a new Button instance using the specified properties.

#### Parameters

##### properties?

[`IButton`](../interfaces/IButton.md)

Properties to set

#### Returns

[`Button`](Button.md)

Button instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:11426](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11426)

Decodes a Button message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Button`](Button.md)

Button

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:11435](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11435)

Decodes a Button message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Button`](Button.md)

Button

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11408](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11408)

Encodes the specified Button message. Does not implicitly [verify](Button.md#verify) messages.

#### Parameters

##### message

[`IButton`](../interfaces/IButton.md)

Button message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11416](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11416)

Encodes the specified Button message, length delimited. Does not implicitly [verify](Button.md#verify) messages.

#### Parameters

##### message

[`IButton`](../interfaces/IButton.md)

Button message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:11449](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11449)

Creates a Button message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Button`](Button.md)

Button

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11457)

Creates a plain object from a Button message. Also converts values to other types if specified.

#### Parameters

##### message

[`Button`](Button.md)

Button

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11442](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11442)

Verifies a Button message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
