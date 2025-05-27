# Class: HSMDateTimeUnixEpoch

Defined in: [WAProto/index.d.ts:14930](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14930)

Represents a HSMDateTimeUnixEpoch.

## Implements

- [`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

## Constructors

### new HSMDateTimeUnixEpoch()

> **new HSMDateTimeUnixEpoch**(`properties`?): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:14936](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14936)

Constructs a new HSMDateTimeUnixEpoch.

#### Parameters

##### properties?

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

Properties to set

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

## Properties

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:14939](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14939)

HSMDateTimeUnixEpoch timestamp.

#### Implementation of

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md).[`timestamp`](../interfaces/IHSMDateTimeUnixEpoch.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15009](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15009)

Converts this HSMDateTimeUnixEpoch to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:14946](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14946)

Creates a new HSMDateTimeUnixEpoch instance using the specified properties.

#### Parameters

##### properties?

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

Properties to set

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

HSMDateTimeUnixEpoch instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:14972](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14972)

Decodes a HSMDateTimeUnixEpoch message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

HSMDateTimeUnixEpoch

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:14981](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14981)

Decodes a HSMDateTimeUnixEpoch message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

HSMDateTimeUnixEpoch

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14954](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14954)

Encodes the specified HSMDateTimeUnixEpoch message. Does not implicitly [verify](HSMDateTimeUnixEpoch.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

HSMDateTimeUnixEpoch message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14962](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14962)

Encodes the specified HSMDateTimeUnixEpoch message, length delimited. Does not implicitly [verify](HSMDateTimeUnixEpoch.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

HSMDateTimeUnixEpoch message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:14995](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14995)

Creates a HSMDateTimeUnixEpoch message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

HSMDateTimeUnixEpoch

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:15003](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15003)

Creates a plain object from a HSMDateTimeUnixEpoch message. Also converts values to other types if specified.

#### Parameters

##### message

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

HSMDateTimeUnixEpoch

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14988](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14988)

Verifies a HSMDateTimeUnixEpoch message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
