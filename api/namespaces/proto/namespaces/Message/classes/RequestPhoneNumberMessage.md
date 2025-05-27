# Class: RequestPhoneNumberMessage

Defined in: [WAProto/index.d.ts:21539](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21539)

Represents a RequestPhoneNumberMessage.

## Implements

- [`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

## Constructors

### new RequestPhoneNumberMessage()

> **new RequestPhoneNumberMessage**(`properties`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:21545](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21545)

Constructs a new RequestPhoneNumberMessage.

#### Parameters

##### properties?

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

Properties to set

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:21548](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21548)

RequestPhoneNumberMessage contextInfo.

#### Implementation of

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md).[`contextInfo`](../interfaces/IRequestPhoneNumberMessage.md#contextinfo)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21618](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21618)

Converts this RequestPhoneNumberMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:21555](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21555)

Creates a new RequestPhoneNumberMessage instance using the specified properties.

#### Parameters

##### properties?

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

Properties to set

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:21581](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21581)

Decodes a RequestPhoneNumberMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:21590](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21590)

Decodes a RequestPhoneNumberMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21563](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21563)

Encodes the specified RequestPhoneNumberMessage message. Does not implicitly [verify](RequestPhoneNumberMessage.md#verify) messages.

#### Parameters

##### message

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

RequestPhoneNumberMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21571](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21571)

Encodes the specified RequestPhoneNumberMessage message, length delimited. Does not implicitly [verify](RequestPhoneNumberMessage.md#verify) messages.

#### Parameters

##### message

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

RequestPhoneNumberMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:21604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21604)

Creates a RequestPhoneNumberMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21612](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21612)

Creates a plain object from a RequestPhoneNumberMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21597](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21597)

Verifies a RequestPhoneNumberMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
