# Class: HSMLocalizableParameter

Defined in: [WAProto/index.d.ts:14486](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14486)

Represents a HSMLocalizableParameter.

## Implements

- [`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

## Constructors

### new HSMLocalizableParameter()

> **new HSMLocalizableParameter**(`properties`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:14492](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14492)

Constructs a new HSMLocalizableParameter.

#### Parameters

##### properties?

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

Properties to set

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

## Properties

### currency?

> `optional` **currency**: `null` \| [`IHSMCurrency`](../namespaces/HSMLocalizableParameter/interfaces/IHSMCurrency.md)

Defined in: [WAProto/index.d.ts:14498](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14498)

HSMLocalizableParameter currency.

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`currency`](../interfaces/IHSMLocalizableParameter.md#currency)

***

### dateTime?

> `optional` **dateTime**: `null` \| [`IHSMDateTime`](../namespaces/HSMLocalizableParameter/interfaces/IHSMDateTime.md)

Defined in: [WAProto/index.d.ts:14501](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14501)

HSMLocalizableParameter dateTime.

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`dateTime`](../interfaces/IHSMLocalizableParameter.md#datetime)

***

### default

> **default**: `string`

Defined in: [WAProto/index.d.ts:14495](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14495)

HSMLocalizableParameter default.

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`default`](../interfaces/IHSMLocalizableParameter.md#default)

***

### paramOneof?

> `optional` **paramOneof**: `"currency"` \| `"dateTime"`

Defined in: [WAProto/index.d.ts:14504](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14504)

HSMLocalizableParameter paramOneof.

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14574](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14574)

Converts this HSMLocalizableParameter to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:14511](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14511)

Creates a new HSMLocalizableParameter instance using the specified properties.

#### Parameters

##### properties?

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

Properties to set

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:14537](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14537)

Decodes a HSMLocalizableParameter message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:14546](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14546)

Decodes a HSMLocalizableParameter message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14519](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14519)

Encodes the specified HSMLocalizableParameter message. Does not implicitly [verify](HSMLocalizableParameter.md#verify) messages.

#### Parameters

##### message

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

HSMLocalizableParameter message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14527](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14527)

Encodes the specified HSMLocalizableParameter message, length delimited. Does not implicitly [verify](HSMLocalizableParameter.md#verify) messages.

#### Parameters

##### message

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

HSMLocalizableParameter message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:14560](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14560)

Creates a HSMLocalizableParameter message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14568](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14568)

Creates a plain object from a HSMLocalizableParameter message. Also converts values to other types if specified.

#### Parameters

##### message

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14553](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14553)

Verifies a HSMLocalizableParameter message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
