# Class: HSMDateTime

Defined in: [WAProto/index.d.ts:14686](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14686)

Represents a HSMDateTime.

## Implements

- [`IHSMDateTime`](../interfaces/IHSMDateTime.md)

## Constructors

### new HSMDateTime()

> **new HSMDateTime**(`properties`?): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:14692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14692)

Constructs a new HSMDateTime.

#### Parameters

##### properties?

[`IHSMDateTime`](../interfaces/IHSMDateTime.md)

Properties to set

#### Returns

[`HSMDateTime`](HSMDateTime.md)

## Properties

### component?

> `optional` **component**: `null` \| [`IHSMDateTimeComponent`](../namespaces/HSMDateTime/interfaces/IHSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:14695](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14695)

HSMDateTime component.

#### Implementation of

[`IHSMDateTime`](../interfaces/IHSMDateTime.md).[`component`](../interfaces/IHSMDateTime.md#component)

***

### datetimeOneof?

> `optional` **datetimeOneof**: `"component"` \| `"unixEpoch"`

Defined in: [WAProto/index.d.ts:14701](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14701)

HSMDateTime datetimeOneof.

***

### unixEpoch?

> `optional` **unixEpoch**: `null` \| [`IHSMDateTimeUnixEpoch`](../namespaces/HSMDateTime/interfaces/IHSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:14698](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14698)

HSMDateTime unixEpoch.

#### Implementation of

[`IHSMDateTime`](../interfaces/IHSMDateTime.md).[`unixEpoch`](../interfaces/IHSMDateTime.md#unixepoch)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14771](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14771)

Converts this HSMDateTime to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:14708](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14708)

Creates a new HSMDateTime instance using the specified properties.

#### Parameters

##### properties?

[`IHSMDateTime`](../interfaces/IHSMDateTime.md)

Properties to set

#### Returns

[`HSMDateTime`](HSMDateTime.md)

HSMDateTime instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:14734](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14734)

Decodes a HSMDateTime message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HSMDateTime`](HSMDateTime.md)

HSMDateTime

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:14743](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14743)

Decodes a HSMDateTime message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HSMDateTime`](HSMDateTime.md)

HSMDateTime

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14716](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14716)

Encodes the specified HSMDateTime message. Does not implicitly [verify](HSMDateTime.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTime`](../interfaces/IHSMDateTime.md)

HSMDateTime message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14724)

Encodes the specified HSMDateTime message, length delimited. Does not implicitly [verify](HSMDateTime.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTime`](../interfaces/IHSMDateTime.md)

HSMDateTime message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:14757](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14757)

Creates a HSMDateTime message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HSMDateTime`](HSMDateTime.md)

HSMDateTime

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14765](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14765)

Creates a plain object from a HSMDateTime message. Also converts values to other types if specified.

#### Parameters

##### message

[`HSMDateTime`](HSMDateTime.md)

HSMDateTime

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14750](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14750)

Verifies a HSMDateTime message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
