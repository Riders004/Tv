# Class: EphemeralSetting

Defined in: [WAProto/index.d.ts:6245](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6245)

Represents an EphemeralSetting.

## Implements

- [`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

## Constructors

### new EphemeralSetting()

> **new EphemeralSetting**(`properties`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:6251](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6251)

Constructs a new EphemeralSetting.

#### Parameters

##### properties?

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

Properties to set

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

## Properties

### duration

> **duration**: `number`

Defined in: [WAProto/index.d.ts:6254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6254)

EphemeralSetting duration.

#### Implementation of

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md).[`duration`](../interfaces/IEphemeralSetting.md#duration)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:6257](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6257)

EphemeralSetting timestamp.

#### Implementation of

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md).[`timestamp`](../interfaces/IEphemeralSetting.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6327](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6327)

Converts this EphemeralSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:6264](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6264)

Creates a new EphemeralSetting instance using the specified properties.

#### Parameters

##### properties?

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

Properties to set

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:6290](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6290)

Decodes an EphemeralSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:6299](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6299)

Decodes an EphemeralSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6272](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6272)

Encodes the specified EphemeralSetting message. Does not implicitly [verify](EphemeralSetting.md#verify) messages.

#### Parameters

##### message

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

EphemeralSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6280](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6280)

Encodes the specified EphemeralSetting message, length delimited. Does not implicitly [verify](EphemeralSetting.md#verify) messages.

#### Parameters

##### message

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

EphemeralSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:6313](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6313)

Creates an EphemeralSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:6321](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6321)

Creates a plain object from an EphemeralSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6306](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6306)

Verifies an EphemeralSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
