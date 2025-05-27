# Class: TimeFormatAction

Defined in: [WAProto/index.d.ts:34009](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34009)

Represents a TimeFormatAction.

## Implements

- [`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

## Constructors

### new TimeFormatAction()

> **new TimeFormatAction**(`properties`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:34015](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34015)

Constructs a new TimeFormatAction.

#### Parameters

##### properties?

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

Properties to set

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

## Properties

### isTwentyFourHourFormatEnabled

> **isTwentyFourHourFormatEnabled**: `boolean`

Defined in: [WAProto/index.d.ts:34018](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34018)

TimeFormatAction isTwentyFourHourFormatEnabled.

#### Implementation of

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md).[`isTwentyFourHourFormatEnabled`](../interfaces/ITimeFormatAction.md#istwentyfourhourformatenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34088](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34088)

Converts this TimeFormatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:34025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34025)

Creates a new TimeFormatAction instance using the specified properties.

#### Parameters

##### properties?

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

Properties to set

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:34051](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34051)

Decodes a TimeFormatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:34060](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34060)

Decodes a TimeFormatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34033](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34033)

Encodes the specified TimeFormatAction message. Does not implicitly [verify](TimeFormatAction.md#verify) messages.

#### Parameters

##### message

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

TimeFormatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34041](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34041)

Encodes the specified TimeFormatAction message, length delimited. Does not implicitly [verify](TimeFormatAction.md#verify) messages.

#### Parameters

##### message

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

TimeFormatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:34074](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34074)

Creates a TimeFormatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34082](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34082)

Creates a plain object from a TimeFormatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34067](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34067)

Verifies a TimeFormatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
