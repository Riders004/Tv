# Class: StatusPSA

Defined in: [WAProto/index.d.ts:29162](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29162)

Represents a StatusPSA.

## Implements

- [`IStatusPSA`](../interfaces/IStatusPSA.md)

## Constructors

### new StatusPSA()

> **new StatusPSA**(`properties`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:29168](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29168)

Constructs a new StatusPSA.

#### Parameters

##### properties?

[`IStatusPSA`](../interfaces/IStatusPSA.md)

Properties to set

#### Returns

[`StatusPSA`](StatusPSA.md)

## Properties

### campaignExpirationTimestamp

> **campaignExpirationTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:29174](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29174)

StatusPSA campaignExpirationTimestamp.

#### Implementation of

[`IStatusPSA`](../interfaces/IStatusPSA.md).[`campaignExpirationTimestamp`](../interfaces/IStatusPSA.md#campaignexpirationtimestamp)

***

### campaignId

> **campaignId**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:29171](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29171)

StatusPSA campaignId.

#### Implementation of

[`IStatusPSA`](../interfaces/IStatusPSA.md).[`campaignId`](../interfaces/IStatusPSA.md#campaignid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29244](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29244)

Converts this StatusPSA to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:29181](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29181)

Creates a new StatusPSA instance using the specified properties.

#### Parameters

##### properties?

[`IStatusPSA`](../interfaces/IStatusPSA.md)

Properties to set

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:29207](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29207)

Decodes a StatusPSA message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:29216](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29216)

Decodes a StatusPSA message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29189](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29189)

Encodes the specified StatusPSA message. Does not implicitly [verify](StatusPSA.md#verify) messages.

#### Parameters

##### message

[`IStatusPSA`](../interfaces/IStatusPSA.md)

StatusPSA message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29197](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29197)

Encodes the specified StatusPSA message, length delimited. Does not implicitly [verify](StatusPSA.md#verify) messages.

#### Parameters

##### message

[`IStatusPSA`](../interfaces/IStatusPSA.md)

StatusPSA message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:29230](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29230)

Creates a StatusPSA message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:29238](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29238)

Creates a plain object from a StatusPSA message. Also converts values to other types if specified.

#### Parameters

##### message

[`StatusPSA`](StatusPSA.md)

StatusPSA

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29223](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29223)

Verifies a StatusPSA message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
