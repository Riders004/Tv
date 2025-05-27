# Class: BusinessMessageForwardInfo

Defined in: [WAProto/index.d.ts:4553](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4553)

Represents a BusinessMessageForwardInfo.

## Implements

- [`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

## Constructors

### new BusinessMessageForwardInfo()

> **new BusinessMessageForwardInfo**(`properties`?): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:4559](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4559)

Constructs a new BusinessMessageForwardInfo.

#### Parameters

##### properties?

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

Properties to set

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

## Properties

### businessOwnerJid

> **businessOwnerJid**: `string`

Defined in: [WAProto/index.d.ts:4562](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4562)

BusinessMessageForwardInfo businessOwnerJid.

#### Implementation of

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md).[`businessOwnerJid`](../interfaces/IBusinessMessageForwardInfo.md#businessownerjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4632](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4632)

Converts this BusinessMessageForwardInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:4569](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4569)

Creates a new BusinessMessageForwardInfo instance using the specified properties.

#### Parameters

##### properties?

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

Properties to set

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

BusinessMessageForwardInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:4595](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4595)

Decodes a BusinessMessageForwardInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

BusinessMessageForwardInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:4604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4604)

Decodes a BusinessMessageForwardInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

BusinessMessageForwardInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4577](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4577)

Encodes the specified BusinessMessageForwardInfo message. Does not implicitly [verify](BusinessMessageForwardInfo.md#verify) messages.

#### Parameters

##### message

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

BusinessMessageForwardInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4585](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4585)

Encodes the specified BusinessMessageForwardInfo message, length delimited. Does not implicitly [verify](BusinessMessageForwardInfo.md#verify) messages.

#### Parameters

##### message

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

BusinessMessageForwardInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:4618](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4618)

Creates a BusinessMessageForwardInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

BusinessMessageForwardInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:4626](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4626)

Creates a plain object from a BusinessMessageForwardInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

BusinessMessageForwardInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4611](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4611)

Verifies a BusinessMessageForwardInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
