# Class: Point

Defined in: [WAProto/index.d.ts:25824](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25824)

Represents a Point.

## Implements

- [`IPoint`](../interfaces/IPoint.md)

## Constructors

### new Point()

> **new Point**(`properties`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:25830](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25830)

Constructs a new Point.

#### Parameters

##### properties?

[`IPoint`](../interfaces/IPoint.md)

Properties to set

#### Returns

[`Point`](Point.md)

## Properties

### x

> **x**: `number`

Defined in: [WAProto/index.d.ts:25839](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25839)

Point x.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`x`](../interfaces/IPoint.md#x)

***

### xDeprecated

> **xDeprecated**: `number`

Defined in: [WAProto/index.d.ts:25833](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25833)

Point xDeprecated.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`xDeprecated`](../interfaces/IPoint.md#xdeprecated)

***

### y

> **y**: `number`

Defined in: [WAProto/index.d.ts:25842](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25842)

Point y.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`y`](../interfaces/IPoint.md#y)

***

### yDeprecated

> **yDeprecated**: `number`

Defined in: [WAProto/index.d.ts:25836](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25836)

Point yDeprecated.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`yDeprecated`](../interfaces/IPoint.md#ydeprecated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25912](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25912)

Converts this Point to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:25849](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25849)

Creates a new Point instance using the specified properties.

#### Parameters

##### properties?

[`IPoint`](../interfaces/IPoint.md)

Properties to set

#### Returns

[`Point`](Point.md)

Point instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:25875](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25875)

Decodes a Point message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Point`](Point.md)

Point

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:25884](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25884)

Decodes a Point message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Point`](Point.md)

Point

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25857](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25857)

Encodes the specified Point message. Does not implicitly [verify](Point.md#verify) messages.

#### Parameters

##### message

[`IPoint`](../interfaces/IPoint.md)

Point message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25865](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25865)

Encodes the specified Point message, length delimited. Does not implicitly [verify](Point.md#verify) messages.

#### Parameters

##### message

[`IPoint`](../interfaces/IPoint.md)

Point message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:25898](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25898)

Creates a Point message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Point`](Point.md)

Point

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:25906](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25906)

Creates a plain object from a Point message. Also converts values to other types if specified.

#### Parameters

##### message

[`Point`](Point.md)

Point

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25891](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25891)

Verifies a Point message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
