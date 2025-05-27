# Class: PhoneNumberToLIDMapping

Defined in: [WAProto/index.d.ts:25496](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25496)

Represents a PhoneNumberToLIDMapping.

## Implements

- [`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

## Constructors

### new PhoneNumberToLIDMapping()

> **new PhoneNumberToLIDMapping**(`properties`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:25502](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25502)

Constructs a new PhoneNumberToLIDMapping.

#### Parameters

##### properties?

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

Properties to set

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

## Properties

### lidJid

> **lidJid**: `string`

Defined in: [WAProto/index.d.ts:25508](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25508)

PhoneNumberToLIDMapping lidJid.

#### Implementation of

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md).[`lidJid`](../interfaces/IPhoneNumberToLIDMapping.md#lidjid)

***

### pnJid

> **pnJid**: `string`

Defined in: [WAProto/index.d.ts:25505](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25505)

PhoneNumberToLIDMapping pnJid.

#### Implementation of

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md).[`pnJid`](../interfaces/IPhoneNumberToLIDMapping.md#pnjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25578)

Converts this PhoneNumberToLIDMapping to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:25515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25515)

Creates a new PhoneNumberToLIDMapping instance using the specified properties.

#### Parameters

##### properties?

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

Properties to set

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:25541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25541)

Decodes a PhoneNumberToLIDMapping message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:25550](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25550)

Decodes a PhoneNumberToLIDMapping message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25523](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25523)

Encodes the specified PhoneNumberToLIDMapping message. Does not implicitly [verify](PhoneNumberToLIDMapping.md#verify) messages.

#### Parameters

##### message

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25531](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25531)

Encodes the specified PhoneNumberToLIDMapping message, length delimited. Does not implicitly [verify](PhoneNumberToLIDMapping.md#verify) messages.

#### Parameters

##### message

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:25564](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25564)

Creates a PhoneNumberToLIDMapping message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:25572](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25572)

Creates a plain object from a PhoneNumberToLIDMapping message. Also converts values to other types if specified.

#### Parameters

##### message

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25557](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L25557)

Verifies a PhoneNumberToLIDMapping message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
