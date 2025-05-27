# Class: Location

Defined in: [WAProto/index.d.ts:8815](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8815)

Represents a Location.

## Implements

- [`ILocation`](../interfaces/ILocation.md)

## Constructors

### new Location()

> **new Location**(`properties`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:8821](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8821)

Constructs a new Location.

#### Parameters

##### properties?

[`ILocation`](../interfaces/ILocation.md)

Properties to set

#### Returns

[`Location`](Location.md)

## Properties

### degreesLatitude

> **degreesLatitude**: `number`

Defined in: [WAProto/index.d.ts:8824](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8824)

Location degreesLatitude.

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`degreesLatitude`](../interfaces/ILocation.md#degreeslatitude)

***

### degreesLongitude

> **degreesLongitude**: `number`

Defined in: [WAProto/index.d.ts:8827](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8827)

Location degreesLongitude.

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`degreesLongitude`](../interfaces/ILocation.md#degreeslongitude)

***

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:8830](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8830)

Location name.

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`name`](../interfaces/ILocation.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8900](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8900)

Converts this Location to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:8837](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8837)

Creates a new Location instance using the specified properties.

#### Parameters

##### properties?

[`ILocation`](../interfaces/ILocation.md)

Properties to set

#### Returns

[`Location`](Location.md)

Location instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:8863](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8863)

Decodes a Location message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Location`](Location.md)

Location

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:8872](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8872)

Decodes a Location message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Location`](Location.md)

Location

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8845](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8845)

Encodes the specified Location message. Does not implicitly [verify](Location.md#verify) messages.

#### Parameters

##### message

[`ILocation`](../interfaces/ILocation.md)

Location message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8853](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8853)

Encodes the specified Location message, length delimited. Does not implicitly [verify](Location.md#verify) messages.

#### Parameters

##### message

[`ILocation`](../interfaces/ILocation.md)

Location message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:8886](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8886)

Creates a Location message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Location`](Location.md)

Location

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8894](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8894)

Creates a plain object from a Location message. Also converts values to other types if specified.

#### Parameters

##### message

[`Location`](Location.md)

Location

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8879](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8879)

Verifies a Location message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
