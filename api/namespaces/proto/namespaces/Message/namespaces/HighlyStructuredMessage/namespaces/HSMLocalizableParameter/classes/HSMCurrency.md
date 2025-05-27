# Class: HSMCurrency

Defined in: [WAProto/index.d.ts:14590](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14590)

Represents a HSMCurrency.

## Implements

- [`IHSMCurrency`](../interfaces/IHSMCurrency.md)

## Constructors

### new HSMCurrency()

> **new HSMCurrency**(`properties`?): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:14596](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14596)

Constructs a new HSMCurrency.

#### Parameters

##### properties?

[`IHSMCurrency`](../interfaces/IHSMCurrency.md)

Properties to set

#### Returns

[`HSMCurrency`](HSMCurrency.md)

## Properties

### amount1000

> **amount1000**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:14602](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14602)

HSMCurrency amount1000.

#### Implementation of

[`IHSMCurrency`](../interfaces/IHSMCurrency.md).[`amount1000`](../interfaces/IHSMCurrency.md#amount1000)

***

### currencyCode

> **currencyCode**: `string`

Defined in: [WAProto/index.d.ts:14599](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14599)

HSMCurrency currencyCode.

#### Implementation of

[`IHSMCurrency`](../interfaces/IHSMCurrency.md).[`currencyCode`](../interfaces/IHSMCurrency.md#currencycode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14672](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14672)

Converts this HSMCurrency to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:14609](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14609)

Creates a new HSMCurrency instance using the specified properties.

#### Parameters

##### properties?

[`IHSMCurrency`](../interfaces/IHSMCurrency.md)

Properties to set

#### Returns

[`HSMCurrency`](HSMCurrency.md)

HSMCurrency instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:14635](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14635)

Decodes a HSMCurrency message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HSMCurrency`](HSMCurrency.md)

HSMCurrency

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:14644](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14644)

Decodes a HSMCurrency message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HSMCurrency`](HSMCurrency.md)

HSMCurrency

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14617](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14617)

Encodes the specified HSMCurrency message. Does not implicitly [verify](HSMCurrency.md#verify) messages.

#### Parameters

##### message

[`IHSMCurrency`](../interfaces/IHSMCurrency.md)

HSMCurrency message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14625)

Encodes the specified HSMCurrency message, length delimited. Does not implicitly [verify](HSMCurrency.md#verify) messages.

#### Parameters

##### message

[`IHSMCurrency`](../interfaces/IHSMCurrency.md)

HSMCurrency message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:14658](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14658)

Creates a HSMCurrency message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HSMCurrency`](HSMCurrency.md)

HSMCurrency

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14666](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14666)

Creates a plain object from a HSMCurrency message. Also converts values to other types if specified.

#### Parameters

##### message

[`HSMCurrency`](HSMCurrency.md)

HSMCurrency

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14651](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14651)

Verifies a HSMCurrency message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
