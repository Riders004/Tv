# Class: ClientFinish

Defined in: [WAProto/index.d.ts:7163](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7163)

Represents a ClientFinish.

## Implements

- [`IClientFinish`](../interfaces/IClientFinish.md)

## Constructors

### new ClientFinish()

> **new ClientFinish**(`properties`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:7169](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7169)

Constructs a new ClientFinish.

#### Parameters

##### properties?

[`IClientFinish`](../interfaces/IClientFinish.md)

Properties to set

#### Returns

[`ClientFinish`](ClientFinish.md)

## Properties

### payload

> **payload**: `Uint8Array`

Defined in: [WAProto/index.d.ts:7175](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7175)

ClientFinish payload.

#### Implementation of

[`IClientFinish`](../interfaces/IClientFinish.md).[`payload`](../interfaces/IClientFinish.md#payload)

***

### static

> **static**: `Uint8Array`

Defined in: [WAProto/index.d.ts:7172](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7172)

ClientFinish static.

#### Implementation of

[`IClientFinish`](../interfaces/IClientFinish.md).[`static`](../interfaces/IClientFinish.md#static)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7245](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7245)

Converts this ClientFinish to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:7182](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7182)

Creates a new ClientFinish instance using the specified properties.

#### Parameters

##### properties?

[`IClientFinish`](../interfaces/IClientFinish.md)

Properties to set

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:7208](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7208)

Decodes a ClientFinish message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:7217](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7217)

Decodes a ClientFinish message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7190](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7190)

Encodes the specified ClientFinish message. Does not implicitly [verify](ClientFinish.md#verify) messages.

#### Parameters

##### message

[`IClientFinish`](../interfaces/IClientFinish.md)

ClientFinish message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7198)

Encodes the specified ClientFinish message, length delimited. Does not implicitly [verify](ClientFinish.md#verify) messages.

#### Parameters

##### message

[`IClientFinish`](../interfaces/IClientFinish.md)

ClientFinish message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:7231](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7231)

Creates a ClientFinish message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:7239](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7239)

Creates a plain object from a ClientFinish message. Also converts values to other types if specified.

#### Parameters

##### message

[`ClientFinish`](ClientFinish.md)

ClientFinish

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7224](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7224)

Verifies a ClientFinish message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
