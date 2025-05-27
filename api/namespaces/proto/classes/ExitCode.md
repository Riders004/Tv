# Class: ExitCode

Defined in: [WAProto/index.d.ts:6449](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6449)

Represents an ExitCode.

## Implements

- [`IExitCode`](../interfaces/IExitCode.md)

## Constructors

### new ExitCode()

> **new ExitCode**(`properties`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:6455](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6455)

Constructs a new ExitCode.

#### Parameters

##### properties?

[`IExitCode`](../interfaces/IExitCode.md)

Properties to set

#### Returns

[`ExitCode`](ExitCode.md)

## Properties

### code

> **code**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:6458](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6458)

ExitCode code.

#### Implementation of

[`IExitCode`](../interfaces/IExitCode.md).[`code`](../interfaces/IExitCode.md#code)

***

### text

> **text**: `string`

Defined in: [WAProto/index.d.ts:6461](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6461)

ExitCode text.

#### Implementation of

[`IExitCode`](../interfaces/IExitCode.md).[`text`](../interfaces/IExitCode.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6531](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6531)

Converts this ExitCode to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:6468](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6468)

Creates a new ExitCode instance using the specified properties.

#### Parameters

##### properties?

[`IExitCode`](../interfaces/IExitCode.md)

Properties to set

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:6494](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6494)

Decodes an ExitCode message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:6503](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6503)

Decodes an ExitCode message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6476](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6476)

Encodes the specified ExitCode message. Does not implicitly [verify](ExitCode.md#verify) messages.

#### Parameters

##### message

[`IExitCode`](../interfaces/IExitCode.md)

ExitCode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6484](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6484)

Encodes the specified ExitCode message, length delimited. Does not implicitly [verify](ExitCode.md#verify) messages.

#### Parameters

##### message

[`IExitCode`](../interfaces/IExitCode.md)

ExitCode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:6517](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6517)

Creates an ExitCode message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:6525](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6525)

Creates a plain object from an ExitCode message. Also converts values to other types if specified.

#### Parameters

##### message

[`ExitCode`](ExitCode.md)

ExitCode

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6510](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6510)

Verifies an ExitCode message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
