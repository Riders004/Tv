# Class: ExtendedTextMessageWithParentKey

Defined in: [WAProto/index.d.ts:14016](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14016)

Represents an ExtendedTextMessageWithParentKey.

## Implements

- [`IExtendedTextMessageWithParentKey`](../interfaces/IExtendedTextMessageWithParentKey.md)

## Constructors

### new ExtendedTextMessageWithParentKey()

> **new ExtendedTextMessageWithParentKey**(`properties`?): [`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

Defined in: [WAProto/index.d.ts:14022](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14022)

Constructs a new ExtendedTextMessageWithParentKey.

#### Parameters

##### properties?

[`IExtendedTextMessageWithParentKey`](../interfaces/IExtendedTextMessageWithParentKey.md)

Properties to set

#### Returns

[`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

## Properties

### extendedTextMessage?

> `optional` **extendedTextMessage**: `null` \| [`IExtendedTextMessage`](../interfaces/IExtendedTextMessage.md)

Defined in: [WAProto/index.d.ts:14028](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14028)

ExtendedTextMessageWithParentKey extendedTextMessage.

#### Implementation of

[`IExtendedTextMessageWithParentKey`](../interfaces/IExtendedTextMessageWithParentKey.md).[`extendedTextMessage`](../interfaces/IExtendedTextMessageWithParentKey.md#extendedtextmessage)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:14025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14025)

ExtendedTextMessageWithParentKey key.

#### Implementation of

[`IExtendedTextMessageWithParentKey`](../interfaces/IExtendedTextMessageWithParentKey.md).[`key`](../interfaces/IExtendedTextMessageWithParentKey.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14098](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14098)

Converts this ExtendedTextMessageWithParentKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

Defined in: [WAProto/index.d.ts:14035](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14035)

Creates a new ExtendedTextMessageWithParentKey instance using the specified properties.

#### Parameters

##### properties?

[`IExtendedTextMessageWithParentKey`](../interfaces/IExtendedTextMessageWithParentKey.md)

Properties to set

#### Returns

[`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

ExtendedTextMessageWithParentKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

Defined in: [WAProto/index.d.ts:14061](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14061)

Decodes an ExtendedTextMessageWithParentKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

ExtendedTextMessageWithParentKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

Defined in: [WAProto/index.d.ts:14070](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14070)

Decodes an ExtendedTextMessageWithParentKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

ExtendedTextMessageWithParentKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14043](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14043)

Encodes the specified ExtendedTextMessageWithParentKey message. Does not implicitly [verify](ExtendedTextMessageWithParentKey.md#verify) messages.

#### Parameters

##### message

[`IExtendedTextMessageWithParentKey`](../interfaces/IExtendedTextMessageWithParentKey.md)

ExtendedTextMessageWithParentKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14051](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14051)

Encodes the specified ExtendedTextMessageWithParentKey message, length delimited. Does not implicitly [verify](ExtendedTextMessageWithParentKey.md#verify) messages.

#### Parameters

##### message

[`IExtendedTextMessageWithParentKey`](../interfaces/IExtendedTextMessageWithParentKey.md)

ExtendedTextMessageWithParentKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

Defined in: [WAProto/index.d.ts:14084](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14084)

Creates an ExtendedTextMessageWithParentKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

ExtendedTextMessageWithParentKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14092](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14092)

Creates a plain object from an ExtendedTextMessageWithParentKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`ExtendedTextMessageWithParentKey`](ExtendedTextMessageWithParentKey.md)

ExtendedTextMessageWithParentKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14077](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14077)

Verifies an ExtendedTextMessageWithParentKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
