# Class: ButtonText

Defined in: [WAProto/index.d.ts:11476](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11476)

Represents a ButtonText.

## Implements

- [`IButtonText`](../interfaces/IButtonText.md)

## Constructors

### new ButtonText()

> **new ButtonText**(`properties`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:11482](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11482)

Constructs a new ButtonText.

#### Parameters

##### properties?

[`IButtonText`](../interfaces/IButtonText.md)

Properties to set

#### Returns

[`ButtonText`](ButtonText.md)

## Properties

### displayText

> **displayText**: `string`

Defined in: [WAProto/index.d.ts:11485](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11485)

ButtonText displayText.

#### Implementation of

[`IButtonText`](../interfaces/IButtonText.md).[`displayText`](../interfaces/IButtonText.md#displaytext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11555](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11555)

Converts this ButtonText to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:11492](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11492)

Creates a new ButtonText instance using the specified properties.

#### Parameters

##### properties?

[`IButtonText`](../interfaces/IButtonText.md)

Properties to set

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:11518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11518)

Decodes a ButtonText message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:11527](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11527)

Decodes a ButtonText message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11500](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11500)

Encodes the specified ButtonText message. Does not implicitly [verify](ButtonText.md#verify) messages.

#### Parameters

##### message

[`IButtonText`](../interfaces/IButtonText.md)

ButtonText message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11508](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11508)

Encodes the specified ButtonText message, length delimited. Does not implicitly [verify](ButtonText.md#verify) messages.

#### Parameters

##### message

[`IButtonText`](../interfaces/IButtonText.md)

ButtonText message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:11541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11541)

Creates a ButtonText message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11549](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11549)

Creates a plain object from a ButtonText message. Also converts values to other types if specified.

#### Parameters

##### message

[`ButtonText`](ButtonText.md)

ButtonText

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11534](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11534)

Verifies a ButtonText message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
