# Class: HSMDateTimeComponent

Defined in: [WAProto/index.d.ts:14802](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14802)

Represents a HSMDateTimeComponent.

## Implements

- [`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

## Constructors

### new HSMDateTimeComponent()

> **new HSMDateTimeComponent**(`properties`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:14808](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14808)

Constructs a new HSMDateTimeComponent.

#### Parameters

##### properties?

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

Properties to set

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

## Properties

### calendar

> **calendar**: [`CalendarType`](../namespaces/HSMDateTimeComponent/enumerations/CalendarType.md)

Defined in: [WAProto/index.d.ts:14829](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14829)

HSMDateTimeComponent calendar.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`calendar`](../interfaces/IHSMDateTimeComponent.md#calendar)

***

### dayOfMonth

> **dayOfMonth**: `number`

Defined in: [WAProto/index.d.ts:14820](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14820)

HSMDateTimeComponent dayOfMonth.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`dayOfMonth`](../interfaces/IHSMDateTimeComponent.md#dayofmonth)

***

### dayOfWeek

> **dayOfWeek**: [`DayOfWeekType`](../namespaces/HSMDateTimeComponent/enumerations/DayOfWeekType.md)

Defined in: [WAProto/index.d.ts:14811](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14811)

HSMDateTimeComponent dayOfWeek.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`dayOfWeek`](../interfaces/IHSMDateTimeComponent.md#dayofweek)

***

### hour

> **hour**: `number`

Defined in: [WAProto/index.d.ts:14823](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14823)

HSMDateTimeComponent hour.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`hour`](../interfaces/IHSMDateTimeComponent.md#hour)

***

### minute

> **minute**: `number`

Defined in: [WAProto/index.d.ts:14826](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14826)

HSMDateTimeComponent minute.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`minute`](../interfaces/IHSMDateTimeComponent.md#minute)

***

### month

> **month**: `number`

Defined in: [WAProto/index.d.ts:14817](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14817)

HSMDateTimeComponent month.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`month`](../interfaces/IHSMDateTimeComponent.md#month)

***

### year

> **year**: `number`

Defined in: [WAProto/index.d.ts:14814](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14814)

HSMDateTimeComponent year.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`year`](../interfaces/IHSMDateTimeComponent.md#year)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14899](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14899)

Converts this HSMDateTimeComponent to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:14836](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14836)

Creates a new HSMDateTimeComponent instance using the specified properties.

#### Parameters

##### properties?

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

Properties to set

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:14862](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14862)

Decodes a HSMDateTimeComponent message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:14871](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14871)

Decodes a HSMDateTimeComponent message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14844](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14844)

Encodes the specified HSMDateTimeComponent message. Does not implicitly [verify](HSMDateTimeComponent.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

HSMDateTimeComponent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14852](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14852)

Encodes the specified HSMDateTimeComponent message, length delimited. Does not implicitly [verify](HSMDateTimeComponent.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

HSMDateTimeComponent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:14885](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14885)

Creates a HSMDateTimeComponent message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14893](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14893)

Creates a plain object from a HSMDateTimeComponent message. Also converts values to other types if specified.

#### Parameters

##### message

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14878](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14878)

Verifies a HSMDateTimeComponent message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
