# Class: Money

Defined in: [WAProto/index.d.ts:23642](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23642)

Represents a Money.

## Implements

- [`IMoney`](../interfaces/IMoney.md)

## Constructors

### new Money()

> **new Money**(`properties`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:23648](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23648)

Constructs a new Money.

#### Parameters

##### properties?

[`IMoney`](../interfaces/IMoney.md)

Properties to set

#### Returns

[`Money`](Money.md)

## Properties

### currencyCode

> **currencyCode**: `string`

Defined in: [WAProto/index.d.ts:23657](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23657)

Money currencyCode.

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`currencyCode`](../interfaces/IMoney.md#currencycode)

***

### offset

> **offset**: `number`

Defined in: [WAProto/index.d.ts:23654](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23654)

Money offset.

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`offset`](../interfaces/IMoney.md#offset)

***

### value

> **value**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:23651](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23651)

Money value.

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`value`](../interfaces/IMoney.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23727](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23727)

Converts this Money to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:23664](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23664)

Creates a new Money instance using the specified properties.

#### Parameters

##### properties?

[`IMoney`](../interfaces/IMoney.md)

Properties to set

#### Returns

[`Money`](Money.md)

Money instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:23690](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23690)

Decodes a Money message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Money`](Money.md)

Money

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:23699](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23699)

Decodes a Money message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Money`](Money.md)

Money

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23672](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23672)

Encodes the specified Money message. Does not implicitly [verify](Money.md#verify) messages.

#### Parameters

##### message

[`IMoney`](../interfaces/IMoney.md)

Money message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23680](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23680)

Encodes the specified Money message, length delimited. Does not implicitly [verify](Money.md#verify) messages.

#### Parameters

##### message

[`IMoney`](../interfaces/IMoney.md)

Money message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:23713](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23713)

Creates a Money message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Money`](Money.md)

Money

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:23721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23721)

Creates a plain object from a Money message. Also converts values to other types if specified.

#### Parameters

##### message

[`Money`](Money.md)

Money

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23706](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23706)

Verifies a Money message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
